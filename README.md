<script>const dom = document.querySelector('.content')
const data = '早安咖啡'.split('')
    let index = 0
    function writing(index) {
        if (index < data.length) {
            dom.innerHTML += data[index]
            setTimeout(writing.bind(this), 200, ++index)
        }
    }

作者：东方石匠
链接：https://juejin.cn/post/6844904006460899335
来源：稀土掘金
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。</script>
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=KvN1027)](https://github.com/anuraghazra/github-readme-stats)
