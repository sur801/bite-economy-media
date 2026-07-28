# bite-economy-media

인스타그램 발행용 렌더 이미지 호스팅.
메타 Graph API 가 이미지를 공개 URL 로 가져가야 해서(cURL) 존재하는 레포다.

- 업로드 주체: `carousel-autopost` 의 `scripts/host_media.py`
- 경로: `media/<account>/<날짜>/slide-NN.jpg`
- 여기 올라가는 것은 인스타에 공개 게시된 이미지뿐이다. 엔진·프롬프트·토큰은 private 레포에 있다.
