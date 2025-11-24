# SoMLib

Unity 프로젝트용 재사용 가능한 라이브러리 모음

## 패키지

### SoMLib.Event
ScriptableObject 기반 이벤트 시스템 (고정 구조체 + 동적 문자열 페이로드)

**설치:**
```
https://github.com/thisis72/SoMLib.Event.git#0.1.0
```

**특징:**
- 고정 구조체 이벤트 (int, Vector3, string, GameObject)
- 동적 문자열 페이로드 (key=value 파싱)
- StringBuilder 풀링으로 GC 최소화
- 런타임/에디터 분리 (Assembly Definition)
- Inspector에서 리스너 목록 확인

**문서:** [SoMLib.Event README](https://github.com/thisis72/SoMLib.Event)

---

## 프로젝트 구조

이 리포지터리는 **데모 Unity 프로젝트**입니다.
- `Assets/SoMLib/Event/` - 로컬 개발 중인 이벤트 시스템 샘플
- 실제 패키지는 별도 리포지터리에서 관리됩니다

## 라이선스

MIT
