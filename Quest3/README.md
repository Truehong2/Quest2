# Code Peer Review Templete

- 코더 : 김진홍님
- 리뷰어 : 김영원

---

# PRT(PeerReviewTemplate)

각 항목을 스스로 확인하고 체크하고 확인하여 작성한 코드에 적용하세요.

- [ ] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
- [o] 주석을 보고 작성자의 코드가 이해되었나요?
- [o] 코드가 에러를 유발할 가능성이 있나요?
- [o] 코드 작성자가 코드를 제대로 이해하고 작성했나요? (직접 인터뷰해보기)
- [o] 코드가 간결한가요?

---

# 예시

1. 코드의 작동 방식을 주석으로 기록합니다.

2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.

3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
   
   ```python

from google.colab import drive
drive.mount('/content/drive') #구글 코랩 드라이브 연동

with open('/content/drive/MyDrive/06TheAvengers.txt', 'r') as f:
  text = f.read()
print(text)                     # 파일 불러오는 코드

text = f

text.lower().split()        # 소문자로 변경해주기, 스플릿 해서 
 
max2gram =  # 텍스트를 받고, 가장 많은 빈도의 두 단어 출력 



if(len())

print(max2gram, countdict[max2gram])
print(Counter(baglist))
   ```
   
   - Code 에 대한 리뷰어의 Comment 를 남겨주세요

전체적으로 방향을 잘 잡으신거 같습니다. 시간이 조금만 더 있었으면 완성을 하셨을 듯 해서 아쉽게 느껴집니다 ㅠㅠ
저는 코랩 연동하는거 뒤늦게 하다가 시간이 다 돼 끝나서 이거 보면서 코랩 연동하는 방식 배워갑니다.

소문자로 변경과 스플릿을 한번에 할 수 있다는 것도 배워갑니다. 작동이 안된다고 하셨는데 37~39줄에서 막히신 듯 하네요! text2 = text.lower().split() 이런식으로 변수 하다 더 생성해서 만드시면 37~39 줄은 작동 되실것 같습니다.
max2gram 변수를 생셩하신걸 보니 위에 코드 해결하시다가 시간이 다 돼 맥스값은 못 구한듯 합니다. 시간이 더 있었으면 분명 좋은 코드 완성 하셨을거에요! 함께 열심히 해봅시다!
---

# 참고 링크 및 코드 개선 여부

```python
#
# 37~39줄에서 막히신 듯 하네요! text2 = text.lower().split() 이런식으로 변수 하다 더 생성해서 만드시면 37~39 줄은 작동 되실것 같습니다.
#
#
```