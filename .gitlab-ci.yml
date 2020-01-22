image: python:3.7.6-buster

before_script:
  - pip install --upgrade pip && pip install -r requirements.txt

pages:
  script:
    - mkdocs build
    - mv site public
  artifacts:
    paths:
    - public
  only:
  - master
