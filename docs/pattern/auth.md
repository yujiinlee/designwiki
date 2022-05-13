---
layout: default
title: "코드/인증"
parent: 패턴별 보기
nav_order: 4
---

# 코드/인증
{: .no_toc }

# 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 코드 입력
2021.11.13 [2021.10 가족계정 인풋 벤치마킹](https://wiki.woowa.in/pages/viewpage.action?pageId=302285938)


{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/02_auth/code" %}
        {%- assign file_path = file.path | absolute_url -%}
[![]({{ file_path }})]({{ file_path }}){% endif %}{%- endfor %}

## 비밀번호
2021.12.22 [P.021 배민페이 비밀번호 개편](https://wiki.woowa.in/pages/viewpage.action?pageId=267630003)

{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/02_auth/password" %}
        {%- assign file_path = file.path | absolute_url -%}
[![]({{ file_path }})]({{ file_path }}){% endif %}{%- endfor %}

## 개인정보 입력

{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/02_auth/enterinfo" %}
        {%- assign file_path = file.path | absolute_url -%}
[![]({{ file_path }})]({{ file_path }}){% endif %}{%- endfor %}
