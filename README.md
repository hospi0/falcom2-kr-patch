# 팔콤 클래식 II (새턴 JP) 한글화

## 내려받기
- 최신 **v0.91** — [릴리즈](https://github.com/hospi0/falcom2-kr-patch/releases/latest)에서 `FalcomClassics2_KR_v0.91.zip`
- 대상: `Falcom Classics II (Japan)` 트랙 1 (트랙 2개)
- 원본md5 `F318CEAB24508302E15DF193F3969373` → 패치md5 `F7385620F3B76EB02E2D8624A63EF6B9`
- 이스 II(대사·아이템·그림 글자·동영상 자막) · 태양의 신전 아스테카 II(대사·그림 글자) · 타이틀 메뉴

## 작업 저장소

- 팔콤 클래식 1편(이스 I·제나두·드래곤 슬레이어)은 별도 저장소 [hospi0/falcom-kr-patch](https://github.com/hospi0/falcom-kr-patch).
- 인계·빌드 절차: **`docs/00_이어하기.md`** 부터.
- 원문 추출: `work/text/*.tsv` · 고친 번역: `work/tr_override` · `work/tr_fix` · `work/tr_add` · 용어 통일 `work/terms.tsv`
- 빌드 `python tools/build_fc2.py --install` → 배포 묶음 `python tools/make_dist.py fc2`
- ROM·빌드 결과물은 들어 있지 않다.
