# upgraded 폴더 구조 설명

`upgraded` 폴더는 레거시(`legacy`) 폴더의 전체 파일과 디렉터리 구조를 복사한 디렉터리입니다. 이 폴더는 기존 레거시 코드를 최신 Python 환경에 맞게 업그레이드하거나 실험하는 공간으로 활용됩니다.

## 주요 하위 폴더 및 파일

- `MANIFEST.in`, `README.rst`, `setup.py`, `distribute_setup.py`, `distribute-0.6.10.tar.gz`: 프로젝트 메타 정보 및 설치 관련 파일
- `docs/`: Sphinx 기반 문서화 폴더
  - `build/`: 빌드된 문서(HTML, doctree 등)
  - `source/`: 문서 소스(rst, conf.py 등)
- `guachi/`: 주요 Python 패키지 소스 코드
  - `__init__.py`, `config.py`, `database.py`: 핵심 모듈
  - `tests/`: 단위 테스트 코드
- `guachi.egg-info/`: 패키징 메타데이터

이 폴더 내의 코드를 최신 Python 문법, 패키징, 테스트 프레임워크(Pytest 등)로 점진적으로 업그레이드할 수 있습니다.

> 참고: 복사된 파일은 레거시 코드와 동일하므로, 업그레이드 실습 및 실험에 자유롭게 활용하세요.
