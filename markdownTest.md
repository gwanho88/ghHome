# 1. 개요

## 본문 1.1

### 맺음말 1.1.1

#### 끝 &nbsp;&nbsp; 1.1.1.1

# 2. 폰트스타일

## 2.1 볼트, 이태릭

### __이 스타일은 볼트 스타일 입니다.__  <-- 볼드

### _이 스타일은 이태릭 스타일입니다._   <-- 이태릭

### `이 문자는 하이라이트가 적용된 문자입니다.` <-- 하이라이트

## 2.2 줄내림

### space 두개 추가 엔터
__이것은__  
_줄내림_  
`입니다.`

## 2.3 인용

이 내용은 네이버 xxx 블로그에서 퍼온 것입니다.

> 네이버 블로그 `http:// blog.naver.com`  
>  [다음 블로그](http:// daum.net)

## 2.4 하이퍼링크 (hyper link)

[이 링크는 네이버로 이동합니다.](https://www.naver.com)

## 이미지 아이콘 삽입

![이미지 링크](http://dbscthumb.phinf.naver.net/2765_000_243/20131031004226275_7IZNV0CGP.jpg/4744186.jpg?type=m4500_4500_fst)


## 표

| 컬럼1 | 컬럼2 | 컬럼3 |
| - | - | - |
| 1 | 2 | 3 |
| 11 | 22 | 33 |

### 정렬

| col1 | col2  | col3  |
|:---|:---:|---:|
| 1234  | 42123  | 321d2 |
| 12 | 123  |  1111 |
| 1  | 4212  | 12  |

## 텍스트 블록

```
 테스트테스트 블록입니다.
```

### 자바스크립트 언어 블록

```JavaScript
 import { Component } from '@angular/core';
import { NavController, NavParams, Platform, LoadingController, ToastController } from 'ionic-angular';
import { TagService } from './tagdetail-service';
import { TagSettingPage } from './tag-setting/tagsetting';
import { Observable } from 'rxjs';
import * as moment from 'moment';
import {pollingTime} from '../../app/const';
import { Global } from '../../app/global';
```

## ordered list unordered list ol,ul tag

### ol
<ol> ol리스트 입니다.
<li> __1__ </li>
<li> _2_ </li>
<li> `3` </li>
</ol>

1. 1번
2. 2번
3. 3번

### ul
<ul> ul리스트 입니다.
<li> 1 </li>
<li> 2 </li>
<li> 3 </li>
</ul>

- 1번
- 2번
- 3번


# preview html로 저장하면 html로 문서가 나옴

rebaseTest2