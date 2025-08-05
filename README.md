# springboot-gradle-common-templete-BOM

## English
BOM simplifies dependency version management by centralizing it, ensuring consistent versions across projects and reducing conflicts.<br>
Updating the BOM automatically updates all managed dependencies, making maintenance easier. In multi-module setups, BOM allows reuse without repeating version declarations, and dependencies can be added without specifying versions, keeping build files clean.

## Korean
BOM은 여러 라이브러리의 버전을 하나로 통합 관리할 수 있어 설정이 간단해지고, 프로젝트 전체에서 버전 일관성을 유지할 수 있습니다.<br>
이를 통해 의존성 충돌을 줄이고, BOM 버전만 변경하면 전체 라이브러리 버전도 함께 업그레이드되어 유지보수가 쉬워집니다.<br>
멀티 모듈 프로젝트에서는 공통 BOM을 공유함으로써 중복 선언 없이 재사용이 가능하며, 하위 모듈에서는 버전 없이도 의존성을 선언할 수 있어 빌드 파일이 간결해집니다.
