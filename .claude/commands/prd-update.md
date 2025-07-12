# [+filename+content] PRD page modification request (prd -> edit prd)

## Function File: Separate filename (TP) and content (WTD) (TP: Target Page, WTE: What To Edit)

{
const firstSpaceIndex = $ARGUMENTS.indexOf(' ');
const TP = firstSpaceIndex === -1 ? $ARGUMENTS : $ARGUMENTS.substring(0, firstSpaceIndex);
const WTE = firstSpaceIndex === -1 ? '' : $ARGUMENTS.substring(firstSpaceIndex + 1);
return TP: ${TP}\nWTE: ${WTE};
}

The TP page needs to reflect how to modify it according to the content of WTE.

## Output

Modify the TP (target page) md file, and if the content changes completely requiring a filename
change, also modify the filename.
