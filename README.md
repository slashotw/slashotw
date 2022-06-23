<script>const dom = document.querySelector('.content')
const data = '早安咖啡'.split('')
    let index = 0
    function writing(index) {
        if (index < data.length) {
            dom.innerHTML += data[index]
            setTimeout(writing.bind(this), 200, ++index)
        }
    }
                                </script>
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=KvN1027)](https://github.com/anuraghazra/github-readme-stats)
