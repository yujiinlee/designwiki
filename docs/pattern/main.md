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
## 국내 커머스

💡 클릭하면 세로로 긴 풀페이지를 보실 수 있습니다.

<!-- 긴 이미지용 div 박스 -->

<div style="display: inline-block;">

{% for file in site.static_files -%}
    {% if file.path contains "/assets/images/page/03_main" %}
        {%- assign file_path = file.path | absolute_url -%}
    <div class="thumbnail-wrapper">
        <a href="{{ file_path }}">
            <img class="longimg" src="{{ file_path }}">
        </a>
    </div>
{% endif %}{%- endfor %}

</div>

<!-- 긴 이미지용 div 박스 -->

-----

## 푸드 딜리버리
