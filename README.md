입력 예시파일 - example_fail, example_success

실행방법 - 입력파일을 프로젝트 path에 포함 후, 콘솔창에 파일 이름을 입력

# Windows

py .\main.py
또는

# mac, linux

python3 main.py
입력 시 정상적으로 GUI실행이 되며(VSCode에서는 실행 버튼 누르시면 됩니다.)

테스트 시에는

# Windows

py .\main.py --test
또는

# mac, linux

python3 main.py --test
입력 시 테스트만 실행됩니다.

# Exmaple 파일 설명

example_fail: 실패한 예시 파일<br>
example_success: 성공한 예시 파일<br><br>

example_engine_1: LOCK상태일 떄만 엔진이 켜지고 꺼지는지 확인<br>
example_engine_2: 속도가 10 이상일 때 엔진이 꺼지지 않는지를 확인<br>
example_engine_3: 트렁크와 문, 문 잠금 상태와 상관없이 켜지고 꺼지는 것이 가능한지를 확인<br><br>

example_lock_1: 속도가 10 이상일 때 동작하지 않음을 확인<br>
example_lock_2: 문이 열린 상태일 때 잠금이 불가능하고, 문이 닫히고, 잠금이 가능함을 확인<br>
example_lock_3: 엔진이 켜진 상태에서 LOCK이 불가능하고 꺼진 상태에서만 LOCK이 가능함을 확인<br>
example_lock_4: 트렁크가 닫힌 상태에서만 LOCK이 가능하고 열린 상태에서는 LOCK이 불가능함을 확인<br><br>

example_accelerate_1: 차량 잠금 상태에서는 가속 및 브레이크가 불가능하고, 잠금 해제 상태에서만 가속 및 브레이크가 가능함을 확인<br>
example_accelerate_2: 엔진이 켜져있는 상태에서만 가속 및 브레이크가 가능함을 확인<br>
example_accelerate_3: 문이 닫힌 상태에서만 가속 패달 작동 가능하고, 문이 열린 상태에서는 가속 패달 작동 불가능함을 확인<br>
example_accelerate_4: 차량의 속도가 0 이상 120 미만에서만 가속 페달 작동이 가능하고 속도가 0을 초과할 때만 브레이크 패달 작동이 가능함을 확인<br><br>

example_trunk_1: 차량 잠금 상태에서는 트렁크가 열리지 않고, 잠금 해제 상태에서만 트렁크가 열림을 확인<br>
example_trunk_2: 차량의 속도가 0일때만 트렁크 열고 닫기가 가능함을 확인<br><br>

example_door_1: 속도가 0일때만 문이 열리고 0이 아닐 때 문이 열리지 않아야 합니다. 또한, 속도와 상관없이 문은 닫혀야 함을 확인<br>
example_door_2: 문이 잠기지 않은 상태에서만 문이 열리고 닫혀야 함을 확인<br>
example_door_3: 자동차 잠금 상태에서는 문이 작동하지 않고 자동차가 잠금 해제 상태에서만 문이 열리고 닫혀야 함을 확인<br><br>

example_door_lock_1: 차량 잠금 해제가 되어야만 문 잠금 및 잠금 해제가 가능함을 확인<br>
example_door_lock_2: 문이 닫힌 상태에서만 문 잠금 및 잠금 해제가 가능함을 확인<br>
example_door_lock_3: 자동차 속도가 0일 때에만 잠금 해제가 가능해야함을 확인<br><br>

example_sos_1: SOS 작동시 속도가 0이 되는지를 확인<br>
example_sos_2: 모든 문의 잠금 상태가 열림으로 설정되어야 하고, 트렁크가 열림을 확인
