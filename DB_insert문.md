> /* 멤버 추가 */

insert into member
		values (seq_member_id.nextval, '닉넴넴', null, 'test@test.com', 'Y', 'Y', '현민현밓','010-1234-1234', 'Y', '1234',
				sysdate, sysdate, 'N', 0, 0, 0, 1, 'Y');
                
                
                
> /* 자게 게시글 추가 */

INSERT INTO board_free VALUES (seq_bf_bno.nextval, 2, 0, 0, '카테고리머지', 
		'자유게시판게시글제목!!', sysdate, sysdate, '출처!!!!', '게시판 내용 뭐넣지!!!!',
		0, 0, 'N');
        
> /* 공유 게시글 추가 */

INSERT INTO board_share VALUES (seq_bs_bno.nextval, 2, '카테고리머지',
	'공유합니당!!!내용이에요!!!!', '공유합니다!!제목이에요', sysdate, sysdate,
	0, 0, 'N');

> /* 나영리 게시글 추가 */

insert into mml_content values (seq_mml_num.nextval, 1, 2, 0, sysdate, sysdate, 
		0, '떠나자!', '안녕핫에요 나영리 컨텐츠에요', '사진링크', 0);

> /* 공지사항 추가 */

INSERT INTO ad_notice VALUES (seq_ad_notice_no.nextval, 1, '공지 내용 뭐넣지!!!!'
    ,'공지사항 제목!!', sysdate, sysdate );

> /* 1:1 문의 등록 */

insert into board_qna values (seq_qna_no.nextval, 2, '문의', '문의제목드립니다.'
		, '문의내용입니다!!!!!!!!!!!!!!!!!!!!11!', sysdate, sysdate, 'N');
    
> /* 1:1 답변 등록 */

insert into ad_qna values (seq_ad_qna_no.nextval, 1, '답변내용입니다!!!!!', sysdate, sysdate, 2);


    
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDg5NDQzOTEyLC0xODQ5MDkxNjcyXX0=
-->