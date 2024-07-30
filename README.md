```bash
!pip install git+https://github.com/term-extraction-project/stop_words.git

from main import get_stop_words
stop_words = get_stop_words()
```

or

```bash
url = 'https://raw.githubusercontent.com/term-extraction-project/stop_words/main/stop_words.txt'
stop_words = (requests.get(url).text).split(",")
```
