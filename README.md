# ansible-playbook-train-role

GPTE advanced deployment ansible 과정 DAY1 세션을 작성한 자료.

1) ROLE based playbook 생성을 실습한 자료이며
2) 중요 변수 설정 변경은 적용하지 않은 상태로 작성되어 있어, 향상의 여지가 있는 자료임
3) ROLES 폴더에는 4가지 role을 모두 가지고 있으며
4) Ansible Galaxy Role 중, PostgreSQL을 search 하고 install 후 init하여 설치하였음


실행은 실습간 플레이북 수정 실행은  
                            ansible-playbook main.yml -e GUID=${GUID} 

ROLE based 플레이북 실행은 
                       ansible-playbook sch-ga.yml -e GUID=${GUID}

입니다.   2020/05/18 작성함.
