메타버스내에서 텍스트형식의 채팅으로 인한 범죄를 회피하기 위한 프로젝트입니다.

본 프로젝트는 2024.06.24. ~ 2024.07.12.의 기간동안 진행되었습니다.

LLM(BERT 모델)응 파인튜닝시킨 AI 모델을 사용하여 실시간으로 메타버스의 채팅을 AI 모델에 전달하여 분류하고 범죄의 유형에 따라 적절한 재재를 가해 메타버스내에서 텍스트형식의 채팅으로 인한 범죄를 회피하기 위한 프로젝트입니다.

구글 데이터셋 서치로 다양하게 습득한 텍스트 범죄 데이터로 학습을 진행하였습니다.

아나콘다 가상환경 설정파일타버스내에서 텍스트형식의 채팅으로 인한 범죄를 회피하기 위한 프로젝트입니다.

본 프로젝트는 2024.06.24. ~ 2024.07.12.의 기간동안 진행되었습니다.

LLM(BERT 모델)응 파인튜닝시킨 AI 모델을 사용하여 실시간으로 메타버스의 채팅을 AI 모델에 전달하여 분류하고 범죄의 유형에 따라 적절한 재재타버스내에서 텍스트형식의 채팅으로 인한 범죄를 회피하기 위한 프로젝트입니다.

구글 데이터셋 서치로 다양하게 습득한 텍스트 범죄 데이터로 학습을 진행하였습니다.

가상환경 설정파일은 CrimeAvoidance.yaml 파일입니다. CNN이라는 이름의 가상환경으로 생성될 것이고, 용량으로 인해 기존에 학습시켜놓았던 파라미터들은 업로드되지 않았습니다.

제재에 해당하는 로직은 Script.lua 파일에 기록되어 있습니다. 해당 로직은 매우 기본적인 악성 채팅 회피 및 차단에 해당하는 제재로, 실시간 채팅 분류를 잘 적용할 수 있는지를 확인하기 위함입니다. 구체적인 제재 방법은 해당 스크립트를 사용자가 api로 받아오는 채팅 분류에 따라 원하는대로 변경할 수 있습니다. Api를 사용하기 위한 url은 ngrok으로 임시로 입력받은 url로 현재는 작동하지 않습니다.
