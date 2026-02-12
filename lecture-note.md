# Reset, Revert, Restore

로컬에서 작업하고, 커밋하고, 아직 push는 안했을 때 : reset 
- 그냥 reset하면 커밋 이력만 삭제됨
- reset --hard 하면 커밋 이력 삭제 + 코드도 원복됨

push까지 해서 소스가 원격에 올라갔는데 원복하고 싶을 때 : revert
- revert 이력이 커밋 이력 뒤로 추가됨 + 코드 원복됨

push 전에, 커밋 전 수정 내용을 지우고 싶을 때 : restore

아직 커밋 안 했다 → restore
커밋 했지만 push 전 → reset
이미 push 했다 → revert
