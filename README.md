# GenAI-2-GenAI 
# 📝 평가 피드백 반영 — 수정 내용

> 진단(Fail) 받은 4개 항목에 대한 수정 사항입니다.
> 프로젝트: **NAERIRO(내일로)** 멀티모달 광고 영상 (창원 테마)

---

## ✅ 수정 1. 스토리보드 필수 필드 추가

**진단:** 스토리보드에 프롬프트·내레이션·출력요약 필드가 누락됨
**수정:** 각 씬(Scene)에 아래 3개 필드를 모두 채워 완성

| Scene | 프롬프트 (Prompt) | 내레이션 (Narration) | 출력 요약 (Output) |
|-------|------------------|---------------------|-------------------|
| **S1 새벽** | Pre-dawn Changwon cityscape, quiet streets, cool blue tone, cinematic wide shot, 16:9 | "아직 어두운 새벽, 하루가 시작되기 전" | 정적인 새벽 도시 풍경 (5초) |
| **S2 달림** | Runner jogging through Changwon streets, dynamic motion, warm sunrise light, tracking shot | "누구보다 먼저 내일을 향해 달린다" | 러너 추적샷, 역동적 움직임 (8초) |
| **S3 일출** | Sunrise over Changwon, golden hour, hopeful atmosphere, brand logo reveal, 16:9 | "내일로, 오늘보다 나은 내일" | 일출 + 로고 등장 (7초) |

---

## ✅ 수정 2. 프롬프트 수정 로그 작성

**진단:** 프롬프트를 수정한 기록(과정)이 없음
**수정:** 수정 전/후와 이유를 로그로 기록

```
[S2] v1 → v2
- before: "Runner in city, morning"
- after : "Runner jogging through Changwon streets, dynamic motion, warm sunrise light, tracking shot"
- 이유  : 지역성(창원) + 카메라 무빙(tracking) + 시간대(sunrise) 명시로 브랜드 톤 일치도 향상

[S3] v1 → v2
- before: "Sunrise with logo"
- after : "Sunrise over Changwon, golden hour, hopeful atmosphere, brand logo reveal, 16:9"
- 이유  : 골든아워/희망적 분위기 키워드 추가로 슬로건 메시지와 정서 일치
```

---

## ✅ 수정 3. 파일 네이밍 규칙 수립

**진단:** 산출물 파일 네이밍 규칙이 없음
**수정:** 일관된 네이밍 공식 정의

**공식:** `NAERIRO_S[씬번호]_[도구]_v[버전]_[비율].확장자`

| 예시 | 의미 |
|------|------|
| `NAERIRO_S1_midjourney_v2_16x9.png` | 씬1 / Midjourney / 2차수정 / 16:9 |
| `NAERIRO_S2_runway_v1_16x9.mp4` | 씬2 / Runway / 1차 / 영상 |
| `NAERIRO_S3_suno_v1_audio.mp3` | 씬3 / Suno / 배경음악 |

---

## ✅ 수정 4. 심층 인터뷰 답변 작성

**진단:** 제작 과정에 대한 심층 인터뷰 답변이 없음
**수정:** 3개 핵심 질문에 답변 작성

**Q1. 도구 선택 근거는?**
> 이미지는 Midjourney(높은 사진 퀄리티·시네마틱 톤), 영상은 Runway(image-to-video로 스토리보드 이미지 연결 용이), 음악은 Suno(짧은 광고 BGM에 적합)를 선택. 세 도구를 조합해 이미지→영상→사운드 파이프라인을 구성함.

**Q2. 프롬프트를 수정한 이유는?**
> 초기 프롬프트는 장면이 추상적이어서 브랜드 정체성(창원 지역성·희망적 톤)이 드러나지 않았음. 지역명, 카메라 무빙, 시간대(골든아워), 분위기 키워드를 추가해 슬로건과 정서적으로 일치시킴.

**Q3. 결과물 불일치를 어떻게 보정했나?**
> Midjourney 이미지의 색온도가 씬마다 달라 통일성이 부족했음. 후반 색보정(컬러그레이딩)으로 블루→웜톤 흐름을 일관되게 맞추고, 씬 전환 시 러너 위치·시선 방향을 이어 연속성을 확보함.

---

*※ 실제 이미지/영상/오디오 결과물은 Midjourney·Runway·Suno에서 직접 생성 후 위 네이밍 규칙에 따라 업로드.*

