## Abstract

This specification defines a model for synchronization and timing of changes to the presentation of a Web page. This specification also defines an application programming interface for interacting with this model and it is expected that further specifications will define declarative means for exposing these features.

## Status of this document

This is a public copy of the editors' draft. It is provided for discussion only and may change at any moment. Its publication here does not imply endorsement of its contents by W3C. Don’t cite this document other than as work in progress.

The (archived) public mailing list public-fx@w3.org (see instructions) is preferred for discussion of this specification. When sending e-mail, please put the text “web-animations” in the subject, preferably like this: “[web-animations] …summary of comment…”

This document was produced by the CSS Working Group (part of the Style Activity) and the SVG Working Group (part of the Graphics Activity).

This document was produced by groups operating under the 5 February 2004 W3C Patent Policy. W3C maintains a public list of any patent disclosures (CSS) and a public list of any patent disclosures (SVG) made in connection with the deliverables of each group; these pages also includes instructions for disclosing a patent. An individual who has actual knowledge of a patent which the individual believes contains Essential Claim(s) must disclose the information in accordance with section 6 of the W3C Patent Policy.

##TODO

鉴于翻译工作的特殊性，需要首先将目录粘贴过来，然后根据目录将需要写的文件按照目录结构构建出图书目录来。我们来写一下这个工序的 IPO 过程图

```
1. read the summary.md file 
2. start from the content or other start point by configed
3. foreach lines
4. trim the line to split with -
5. switch different style of the line
6. get the number string before alphabeta(1., 1.1., 2.2. .etc)
7. case '1.' -> [1.this is test](this-is-test/README.md)
	6.1. mkdir this-is-test && cd $_
	6.2. touch README.md
	6.3. cd ..
8. case '1.1.' ->[1.1 this is second](this-is-test/this-is-second.md)
	7.1. cd this-is-test
	7.2 touch this-is-second.md
	7.3 cd ..
9. things redone as before
```

