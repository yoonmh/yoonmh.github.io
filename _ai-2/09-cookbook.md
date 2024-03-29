---
title: "ChatGPT Cookbook"
layout: single
---

> OpenAI CookBook의 예를 통해 ChatGPT의 기능과 동작을 학습

## ChatGPT 주요 링크
* OpenAI 홈 : [https://openai.com/][1-1]
* ChatGPT 홈 : [https://chat.openai.com/][1-2]
* OpenAI Platform 홈 : [https://platform.openai.com/][1-3]
  * API 레퍼런스 : [https://platform.openai.com/docs/api-reference][1-4]
  * 웹에서 설명한 사용 예제 : [https://platform.openai.com/examples][1-5]
* OpenAI API CookBook : [https://github.com/openai/openai-cookbook][1-6]
* CookBook 강의([임도형 Github 참조][0])

## ChatGPT 계정 만들기
* ChatGPT API Key 발급 ([OpenAI Platform][1-3])
  * 오른쪽 상단 유저 프로파일에서 [View API Keys][1-7] 클릭
  * 중간에 + Create new secret key 버튼을 누르고 API Key 생성
  * 왼쪽 메뉴 [Usage][1-8]에서 사용량 확인(처음 계정을 만들면 $5 credit을 줌)
* 결제 정보 입력 ([Billing][1-9])
  * Start payment plan -> Individual -> Setup payment plan
* [ChatGPT Pricing][1-10]
  * [알아야 할 숫자들][1-11]
  * [원 Article][1-12]

## OpenAI API
* playground : [https://platform.openai.com/playground][2-1]
* doc 홈 : [https://platform.openai.com/docs/introduction][2-2]
* Reference 홈 : [https://platform.openai.com/docs/api-reference][2-3]
* Examples : [https://platform.openai.com/examples][2-4]
* 파인튜닝 공식 문서 : [https://platform.openai.com/docs/guides/fine-tuning][2-5]

## OpenAI API CookBook
* (1) [Github Cookbook][1-6]에서 Codespace 생성
* (2) 호출 기본 방법
  * [호출 최소 코드][3-1]
  * [Tiny Chatbot][3-2]
  * [How to format inputs to ChatGPT models][3-3]
* (3) 토커니아징, 임베딩
  * 토크나이징 : [How to count kokens with tictoken][3-4]
  * 입베딩 : [임베딩 소개글][3-5], [Get embeddings][3-6], [Obtain dataset][3-7]
  * Word 임베딩 예 : [Text tokenizing and embedding][3-8]
* (4) 임베딩을 사용한 사례
  * 검색 : [Semantic text search using embeddings][4-1]
  * 분류 : [Zero-shot classification with embeddings][4-2]
  * 추천 : [Recommendation using embeddings][4-3]
* (5) 파인 튜닝 방법
  * [How_to_finetune_chat_models][5-1]
  * [Fine-tuned_classification][5-2]
* (6) SQL
  * SQL 생성 방법 : [Backtranslation_of_SQL_queries][6-1], [SQL_generation_설명][6-2]
  * Latex 문서의 번역 방법 : [book_translation/translate_latex_book][6-3]
* (7)
  
## 자료
* [ChatGPT_소개][r1]
* GPT 구조 : from_DNN_to_GPT.pptx
* 실습 준비 : OpenAI_계정만들기_키만들기_결제정보_입력.pdf
* OpenAI_API_사용_기초.pdf
* 회자별_실습내용.md

## 3. OpenAI Cookbook
* [ChatGPT 소개][33-1]
* [ChatGPT 구조][33-2]
* [OpenAI 계정 준비][33-3]
* [OpenAI API 사용기초][33-4]
* [OpenAI Cookbook][33-5]
  * [How to format inputs to ChatGPT][33-5-1]
  * [Fine-tuned_classification][33-5-3]
* [ChatGPT로 커스텀 QA엔진 만들기][33-6]
* [OpenAI API][33-7]
  * [API reference][33-7-1]
  * [examples][33-7-2]
* [Awesom Prompt][33-8]
* [DeepLearning.ai의 Prompt Engineering 교육][33-9]
* [OpenAI API 실습자료][33-10]

[0]: https://github.com/dhrim/2023_openai_cookbook
[1-1]: https://openai.com/
[1-2]: https://chat.openai.com/
[1-3]: https://platform.openai.com/
[1-4]: https://platform.openai.com/docs/api-reference
[1-5]: https://platform.openai.com/examples
[1-6]: https://github.com/openai/openai-cookbook
[1-7]: https://platform.openai.com/account/api-keys
[1-8]: https://platform.openai.com/account/usage
[1-9]: https://platform.openai.com/account/billing/overview
[1-10]: https://openai.com/pricing
[1-11]: https://codeendeavor.tistory.com/9
[1-12]: https://github.com/ray-project/llm-numbers
[2-1]: https://platform.openai.com/playground
[2-2]: https://platform.openai.com/docs/introduction
[2-3]: https://platform.openai.com/docs/api-reference
[2-4]: https://platform.openai.com/examples
[2-5]: https://platform.openai.com/docs/guides/fine-tuning
[3-1]: https://colab.research.google.com/drive/1VaqyTynVRLQ0ZOtGCC69e6uwLLs6EYRD
[3-2]: https://colab.research.google.com/drive/1VavGIkcKpDc7A-jxCxCp5eTMOjye0PR6
[3-3]: https://colab.research.google.com/drive/1VeLmhmG5i2493jUTnmmq71idq9LciFqw
[3-4]: https://colab.research.google.com/drive/1VcxZe0e_aUjMrAHjMyPzdPalLmGnZ1VJ
[3-5]: https://openai.com/blog/introducing-text-and-code-embeddings
[3-6]: https://colab.research.google.com/drive/1VogjSe_EehtPxr4Ply7_I6ZxCu2GSACU
[3-7]: https://colab.research.google.com/drive/1VjN8ahHeWdEicMfBD6yMqqpOshXMcBWb
[3-8]: https://colab.research.google.com/drive/1VxXZ4OgsFB0jYs3XG5geFL_um2ECLRqw
[4-1]: https://colab.research.google.com/drive/1W-RPLI6yOw1tmXoNGu4cuGqw4A-I7dI7
[4-2]: https://colab.research.google.com/drive/1W9Hu0UeFM2pPrezvabKWmy2p7AxfULuo
[4-3]: https://colab.research.google.com/drive/1W8iq6Pbsesed-GKdsP3dLktiX2apnCe0
[5-1]: https://colab.research.google.com/drive/1WQQSOSDVq2YCRGMmXXCwkgA84Va-3IYc
[5-2]: https://colab.research.google.com/drive/1WSR29ZFYdjdgrmlECNuUEnpfi9wMQybg
[6-1]: https://colab.research.google.com/drive/1WV4CxuNPjGKcw1Pme7usDt0N-7MhA_TP


[r1]: https://drive.google.com/file/d/1UmD6ij3fw236AlpLS8rSNVb58v_Varxu/view

[33-1]: https://drive.google.com/file/d/16xjN-PxjTl2eK1pGPWZ3t1osLZ4Ny73K
[33-2]: https://docs.google.com/presentation/d/171LwXWTrK6q7cDLFCT9GyT5gqoy9Kqqr
[33-3]: https://drive.google.com/file/d/16xELH8gpjXmQPj5kwNgQ69uDfDFk_5CG
[33-4]: https://drive.google.com/file/d/171miVjHEv9Gv3k4vwAIIoQEEvBBdxsjy/view?usp=drive_link
[33-5]: https://github.com/openai/openai-cookbook
[33-6]: https://drive.google.com/file/d/17CrEmVlveJkVk3o9XA4L04TM7pvuw_fw/view?usp=drive_link
[33-7]: https://platform.openai.com/
[33-7-1]: https://platform.openai.com/docs/api-reference
[33-7-2]: https://platform.openai.com/examples
[33-8]: https://prompts.chat/
[33-9]: https://learn.deeplearning.ai/chatgpt-prompt-eng
[33-10]: https://docs.google.com/presentation/d/178Jj3tLOVmHqCuBSgZ-9EaPZ99pN4MZd

