---
theme: apple-basic
background: https://images.unsplash.com/photo-1659019722197-8ec84ff3df8a?w=1280&fit=crop
title: Microservice for Langsa
highlighter: shiki
drawings:
  persist: false
mdc: true

transition: slide-left
layout: intro
---
Langsa를 위한

# 마이크로서비스

<div class="absolute bottom-10 ">
  <span class="font-700 text-gray-500">
    Langsa G.R
  </span>
</div>



---
## transition: fade-out
---
# <span v-mark.underline.orange>시스템</span>

<img src="https://raw.githubusercontent.com/timbel-net/slide-msa4langsa/main/system.svg" alt="system architecture" />  
<a class="absolute right-10 text-xs" href="https://drive.google.com/file/d/1MbKUIgtzr3DTeWBfU8xCq7T9bWPZvtYy/view?usp=sharing">이미지 편집 공유</a>



---
layout: fact
---
# Discovery & Registration
서비스 인스턴스(or 컨테이너)들을 찾는 방법

<h3 v-click class="transition-opacity delay-300 !text-2xl">Netflix Eureka</h3>



---
layout: fact
---
# Gateway

다양한 서비스, 다양한 조건의 Endpoint 들을 연결하기

<h3 v-click class="transition-opacity delay-300 !text-2xl">
  Spring Cloud Gateway
  & <a href="https://www.npmjs.com/package/@timbel-net/msa-express">@timbel-net/msa-express</a>
</h3>



---
layout: fact
---
# Configure

확장 되는 서비스들을 제어하기

<h3 v-click class="transition-opacity delay-300 !text-2xl text-center">Spring Cloud Config<br>& (Bus) Refresh</h3>



---
layout: fact
---
# Distributed Tracing

분산된 서비스들을 추적하기

<h3 v-click class="transition-opacity delay-300 !text-2xl text-center">Zipkin</h3>



---
layout: fact
---
# Health check

수많은 서비스들의 활성화 상태 확인하기

<h3 v-click class="transition-opacity delay-300 !text-2xl text-center">
  Spring Boot Actuator<br>
  & <a href="https://g.co/gemini/share/a3734854c174">Express Middlewares</a>
</h3>



---
layout: fact
---
# Circuit Breaker

<span class="text-gray-500">TODO</span> 폭주해서 나가떨어진 서비스에 대한 회로 차단기



---
layout: fact
---
# Logging

<span class="text-gray-500">TODO</span> 흩뿌려진 서비스 로그를 한데 모아보기



---
layout: fact
---
# Monitoring

<span class="text-gray-500">TODO</span> 마음의 안정을 위한 최소한의 방비책



---
layout: fact
---
# CI/CD

<span class="text-gray-500">TODO</span> 불로장생(不老長生)을 위한 Blue-Green Deployment(무중단 배포)
