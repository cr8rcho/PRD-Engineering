# [+파일명+내용] prd 페이지 수정 요청 (prd -> edit prd)

## 기능 파일: 파일명(TP)과 내용(WTD) 분리 (TP: Target Page, WTE: What To Edit)

{
const firstSpaceIndex = $ARGUMENTS.indexOf(' ');
const TP = firstSpaceIndex === -1 ? $ARGUMENTS : $ARGUMENTS.substring(0, firstSpaceIndex);
const WTE = firstSpaceIndex === -1 ? '' : $ARGUMENTS.substring(firstSpaceIndex + 1);
return `TP: ${TP}\nWTE: ${WTE}`;
}

TP 페이지에 WTE 의 내용 처럼 어떻게 수정할지를 반영해야 돼.

## 출력

TP(target page) md 파일을 수정, 내용이 완전히 바껴서 파일명을 바꿔야 된다면 파일명도 수정.
