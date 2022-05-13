---
layout: default
title: 온보딩
parent: 패턴별 보기
nav_order: 1
---

# 온보딩
{: .no_toc }

# 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

출처: 2022.01.13 
[2022.01 회원가입 디자인/사용성 개선](https://wiki.woowa.in/pages/viewpage.action?pageId=302285938)

## 회원가입

### SNS 로그인 강조 

{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/01_signin/01" %}
        {%- assign file_path = file.path | absolute_url -%}
[![]({{ file_path }})]({{ file_path }}){% endif %}{%- endfor %}

### SNS/이메일 동일레벨로 표현  

{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/01_signin/02" %}
        {%- assign file_path = file.path | absolute_url -%}
[![]({{ file_path }})]({{ file_path }}){%- endif -%}{%- endfor %}

## 튜토리얼

{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/01_signin/tutorial" %}
        {%- assign file_path = file.path | absolute_url -%}
[![]({{ file_path }})]({{ file_path }}){% endif %}{%- endfor %}
