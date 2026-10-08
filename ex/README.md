# COSE212 예제 ex00–ex08

[2026년 2학기 강의 페이지](https://plrg.korea.ac.kr/courses/cose212/2026_2/)에 연결된 공식 문제 설명과 [ku-plrg-classroom](https://github.com/ku-plrg-classroom)의 풀이용 Scala 템플릿을 각 폴더에 모았습니다. 각 폴더는 독립적인 `sbt` 프로젝트입니다. 문제 풀이 파일은 `src/main/scala/kuplrg/Implementation.scala`이고, 테스트는 `src/test/scala/kuplrg/Spec.scala`에 추가할 수 있습니다. 공통 지침은 [scala.md](scala.md)를 참고하세요.

| 폴더 | 주제 | 공식 문서 |
| --- | --- | --- |
| ex00 | Scala tutorial | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/scala/scala-tutorial) |
| ex01 | AE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/ae) |
| ex02 | VAE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/vae) |
| ex03 | F1VAE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/f1vae) |
| ex04 | FVAE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/fvae) |
| ex05 | RFAE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/rfae) |
| ex06 | BFAE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/bfae) |
| ex07 | MFAE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/mfae) |
| ex08 | LFAE | [문제](https://github.com/ku-plrg-classroom/docs/tree/main/cose212/lfae) |

## 실행

JDK 21 또는 17과 `sbt`가 필요합니다. macOS에서 설치된 JDK 21을 선택하려면 터미널에서 다음을 실행하세요.

```sh
export JAVA_HOME=$(/usr/libexec/java_home -v 21)
export PATH="$JAVA_HOME/bin:$PATH"
cd ex01
sbt test
```

다른 예제는 `cd ex00` 등 해당 폴더로 이동해 실행하세요. 처음 실행할 때 의존성 다운로드로 시간이 걸릴 수 있습니다. 편집기에서 Scala Metals를 사용한다면 `build.sbt`가 있는 **각 ex 폴더**를 프로젝트 루트로 여세요.

Cursor에서는 해당 폴더를 열고 Scala (Metals) 확장을 설치한 뒤 `Metals: Import build`를 실행하면 됩니다. GitHub Codespaces를 쓰려면 이 폴더들을 본인 GitHub 저장소에 올린 다음 Codespace를 만드세요. Codespaces의 터미널에서도 JDK 21/17과 sbt를 준비하고 위 명령을 실행할 수 있습니다. 브라우저의 `github.dev` 편집기는 Java 실행 환경이 없으므로 이 과제를 실행할 수 없습니다.
