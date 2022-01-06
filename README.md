# intellij git trouble QandA
동료들에게 Git 사용과 관련된 문제에 대해 비슷한 질문을 반복해서 받는 것 같습니다. Q&A 들을 간단히 정리해 둡니다. 

※ 저희팀은 IntelliJ 기반 Git GUI를 사용합니다. 그래서 git command 대신, IntelliJ 메뉴를 설명합니다.

# 버전활용
[Q : A소스 코드 N라인 누가 마지막에 수정한거지?](https://github.com/Jsing/intellij-git-trouble-qanda/blob/2d054e70d253cf3aa4f5e1d97cefb12d279f9a44/%EB%B2%84%EC%A0%84%ED%99%9C%EC%9A%A9/A%EC%86%8C%EC%8A%A4%20%EC%BD%94%EB%93%9C%20N%EB%9D%BC%EC%9D%B8%20%EB%88%84%EA%B0%80%20%EB%A7%88%EC%A7%80%EB%A7%89%EC%97%90%20%EC%88%98%EC%A0%95%ED%95%9C%EA%B1%B0%EC%A7%80%3F.md)  

# 충돌
[Q : 충돌이 왜 나는 거야?](https://github.com/Jsing/intellij-git-trouble-qanda/blob/1bae99cc5506079265b95accf435155d93811864/%EC%B6%A9%EB%8F%8C/Q%20:%20%EC%B6%A9%EB%8F%8C%EC%9D%B4%20%EC%99%9C%20%EB%82%98%EB%8A%94%20%EA%B1%B0%EC%95%BC%3F.md)  
[Q : 그래서 충돌은 어떻게 해결해?](https://github.com/Jsing/intellij-git-trouble-qanda/blob/1bae99cc5506079265b95accf435155d93811864/%EC%B6%A9%EB%8F%8C/Q%20:%20%EC%B6%A9%EB%8F%8C%EC%9D%B4%20%EC%99%9C%20%EB%82%98%EB%8A%94%20%EA%B1%B0%EC%95%BC%3F.md) 

# 돌아가기
[Q : 지금 뭔가 잘못 코딩하고 있는 것 같아. 직전 커밋 상태로 깨끗하게 돌리고 싶어. ](https://github.com/Jsing/intellij-git-trouble-qanda/blob/c6b5553285e6b0e63023800674e53c73651626a6/%EB%8F%8C%EC%95%84%EA%B0%80%EA%B8%B0/Q%20:%20%EC%A7%80%EA%B8%88%20%EB%AD%94%EA%B0%80%20%EC%9E%98%EB%AA%BB%20%EC%BD%94%EB%94%A9%ED%95%98%EA%B3%A0%20%EC%9E%88%EB%8A%94%20%EA%B2%83%20%EA%B0%99%EC%95%84.%20%EC%A7%81%EC%A0%84%20%EC%BB%A4%EB%B0%8B%20%EC%83%81%ED%83%9C%EB%A1%9C%20%EA%B9%A8%EB%81%97%ED%95%98%EA%B2%8C%20%EB%8F%8C%EB%A6%AC%EA%B3%A0%20%EC%8B%B6%EC%96%B4.md)  
[Q : 특정 커밋의 변경사항을 되돌려야 하는데, 다음에 다시 사용하게 이력은 남기고 싶어 ](https://github.com/Jsing/intellij-git-trouble-qanda/blob/63f9801b5658502c8167bb3dc4bd3ed190cf2464/%EB%8F%8C%EC%95%84%EA%B0%80%EA%B8%B0/Q%20:%20%ED%8A%B9%EC%A0%95%20%EC%BB%A4%EB%B0%8B%EC%9D%98%20%EB%B3%80%EA%B2%BD%EC%82%AC%ED%95%AD%EC%9D%84%20%EB%90%98%EB%8F%8C%EB%A0%A4%EC%95%BC%20%ED%95%98%EB%8A%94%EB%8D%B0,%20%EB%8B%A4%EC%9D%8C%EC%97%90%20%EB%8B%A4%EC%8B%9C%20%EC%82%AC%EC%9A%A9%ED%95%98%EA%B2%8C%20%EC%9D%B4%EB%A0%A5%EC%9D%80%20%EB%82%A8%EA%B8%B0%EA%B3%A0%20%EC%8B%B6%EC%96%B4%20.md)  
[Q : 뭔가 완전히 잘못되었어! 브랜치를 특정 커밋 지점으로 완전히 돌아가고 싶어! 커밋된 변경도 다 삭제하고 싶어!]()  
[Q : 브랜치를 특정 커밋 지점으로 돌리면서, 해당 커밋 이후에 발생한 변경 사항들은 워킹 디렉토리에 유지하고 싶어. ](https://github.com/Jsing/intellij-git-trouble-qanda/blob/c2ffabfcad778247c2780188efecf502a9933257/%EB%8F%8C%EC%95%84%EA%B0%80%EA%B8%B0/Q%20:%20%EB%B8%8C%EB%9E%9C%EC%B9%98%EB%A5%BC%20%ED%8A%B9%EC%A0%95%20%EC%BB%A4%EB%B0%8B%20%EC%A7%80%EC%A0%90%EC%9C%BC%EB%A1%9C%20%EB%8F%8C%EB%A6%AC%EB%A9%B4%EC%84%9C,%20%ED%95%B4%EB%8B%B9%20%EC%BB%A4%EB%B0%8B%20%EC%9D%B4%ED%9B%84%EC%97%90%20%EB%B0%9C%EC%83%9D%ED%95%9C%20%EB%B3%80%EA%B2%BD%20%EC%82%AC%ED%95%AD%EB%93%A4%EC%9D%80%20%EC%9B%8C%ED%82%B9%20%EB%94%94%EB%A0%89%ED%86%A0%EB%A6%AC%EC%97%90%20%EC%9C%A0%EC%A7%80%ED%95%98%EA%B3%A0%20%EC%8B%B6%EC%96%B4.md)  

# 버전관리


# 커밋 수정하기
- Rebase -i 
- Squash
- Amend 
- Fixup

# 편리한 커밋 메시지
- 커밋 메시지 히스토리
