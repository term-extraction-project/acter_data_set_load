from sklearn.feature_extraction.text import ENGLISH_STOP_WORDS
import requests

url = 'https://gist.githubusercontent.com/ZohebAbai/513218c3468130eacff6481f424e4e64/raw/b70776f341a148293ff277afa0d0302c8c38f7e2/gist_stopwords.txt'
stopwords = (requests.get(url).text).split(",")

add_stop = ['said', 'say', '...', 'like', 'cnn', 'ad', 'etc', 'aforementioned', 'accordance', 'according', 'do', 'did', 'does', 'done', 'possible',
           'consider', 'concern', 'concerning', 'conсerned', 'regard', 'regarding', 'regards', 'have', 'has', 'had', 'having', 'refer', 'referred', 'shall'] # away too much almost other actually other скачать с сайта по in hanced stop word list

stop_words = ENGLISH_STOP_WORDS.union(add_stop)
stop_words = stop_words.union(stopwords)
except_w=['across',"acute","dyspnea" 'act', 'amount', 'announce', 'arise', 'begin', 'beginning', 'beginnings', 'begins', 'believe', 'bill', 'bottom', 'brief', 'call', 'changes', 'course',
          'date', 'detail', 'down', 'effect', 'eight', 'eighty', 'eleven', 'empty', 'end', 'ending', 'fifteen', 'fifth', 'fill', 'fire', 'first', 'five', 'fix', 'forth',
          'forty', 'four', 'front', 'full', 'help', 'home', 'hundred', 'index', 'information', 'inner', 'interest', 'invention', 'left', 'line', 'little', 'made', 'make',
          'makes', 'mill', 'mug', 'name', 'new', 'nine', 'ninety', 'non', 'novel', 'off', 'old', 'on', 'one', 'outside', 'over', 'owing', 'own', 'page', 'pagecount', 'pages',
          'part', 'past', 'placed', 'plus', 'research', 'research-articl', 'results', 'right', 'second', 'section', 'self', 'sent', 'seven', 'side', 'six', 'sixty', 'stop',
          'system', 'thin', 'think', 'third', 'thousand', 'three', 'tip', 'twelve', 'twenty', 'twice', 'two', 'use', 'value', 'way', 'words', 'world', 'zero']

stop_words=stop_words-set(except_w)

class get_stop_words:
    def __init__(self):
        return stop_words
