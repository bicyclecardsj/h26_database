# SQL 학습 내용 요약

Oracle SQL 기반 데이터베이스 설계, 뷰(View) 생성, 조인 및 서브쿼리 활용 실습 기록입니다.

---

## 📌 주요 학습 항목

* **View 생성 및 제약 조건 설정**
  * `CREATE VIEW` 및 `CREATE OR REPLACE VIEW`를 활용한 가상 테이블 정의
  * `WITH READ ONLY` 옵션을 통한 뷰의 데이터 수정 제한
  * `WITH CHECK OPTION`을 활용해 조건에 맞는 데이터만 입력되도록 제약 설정

* **다중 테이블 조인 (Join)**
  * `INNER JOIN`, `LEFT/RIGHT/FULL OUTER JOIN`, `CROSS JOIN` 실습
  * 복수 테이블 결합을 통한 종합 정보 추출 및 뷰 정의

* **서브쿼리 및 집계 기능**
  * `GROUP BY` 및 `HAVING` 절을 사용한 데이터 그룹화 및 통계 조회
  * Inline View, 상관 서브쿼리, `EXISTS`, `IN`, `ALL`, `ANY` 등 복합 조건 처리
  * `FETCH FIRST` 절을 활용한 TOP-N 데이터 추출

---

## 💡 핵심 요약

* **추상화**: 복잡한 조인과 집계 연산을 단일 뷰로 정의하여 쿼리 재사용성을 높임.
* **무결성 보안**: 읽기 전용 뷰 및 조건 체크 옵션으로 원본 데이터의 안전성 확보.
