---
layout: default
title: 메인 페이지
parent: 패턴별 보기
nav_order: 2
---

# 메인 페이지
{: .no_toc }

# 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

출처: 2022.01.13 
[2022.01 회원가입 디자인/사용성 개선](https://wiki.woowa.in/pages/viewpage.action?pageId=302285938)


{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/03_main" %}
        {%- assign file_path = file.path | absolute_url -%}
[![]({{ file_path }})]({{ file_path }}){% endif %}{%- endfor %}

## 푸드 딜리버리
