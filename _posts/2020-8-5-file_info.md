---
title: "file_info reference"
categories: "file_info"
---
### file_info
reference

get_byteArr(file_obj)

파일을 0~256 숫자들의 배열로 변환



get_fileSize(byteArr)

파일의 크기(바이트) 반환



get_freqList(byteArr, fileSize)

숫자의 갯수를 파일 크기로 나눈 소수값으로 이루어진 배열 반환



get_entropy(freqList) 

파일의 엔트로피 반환 (=<8.0)



all(file_obj)
클래스 형태

*info.byteArr

*info.fileSize

*info.freqList

*info.entropy
