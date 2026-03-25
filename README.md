# 출퇴근 기록 관리 웹앱

웹앱 링크: [https://your-username.github.io/your-repo](https://0vollov0.github.io/commute-repository/)

모바일 환경에 최적화된 출퇴근 시간 기록 웹앱입니다.

LocalStorage를 활용하여 별도의 서버 없이 데이터를 저장하고 관리할 수 있습니다.

---

## 주요 기능

* 모바일 최적 카드형 UI
* 모달을 통한 데이터 입력
* 즉시 수정 (inline editing)
* 소요 시간 자동 계산
* LocalStorage 기반 데이터 저장
* 엑셀 다운로드 (.xlsx)
* 출근 / 퇴근 구분 표시

---

## Page



---

## 데이터 구조

```json
[
  {
    "date": "2026-03-25",
    "type": "출근",
    "start": "08:30",
    "end": "09:10",
    "memo": "버스"
  }
]
```

---

## 동작 방식

* 데이터는 브라우저 LocalStorage에 저장됩니다.
* 새로고침 후에도 데이터는 유지됩니다.
* 서버 없이 동작하는 정적 웹 애플리케이션입니다.

---

## 기술 스택

* HTML
* Tailwind CSS
* JavaScript (Vanilla)
* LocalStorage
* SheetJS (xlsx)

---

## 향후 개선

* 주간 / 월간 통계 기능
* 이동 시간 평균 계산
* 클라우드 백업
* PWA 적용
* 필터 및 검색 기능

---

## 라이선스

MIT License
