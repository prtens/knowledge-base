# 青果系统数据库数据字典

数据库名称 jwgldb

## a_test(视图)
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|xh | char(12) |  | NO  |  	 |  	 |
|choose_id | int(11) |   | NO  |   | 	 	| 
|KCID | varchar(8) |  | YES  |   | 	 	| 
|T_ZJJS | char(10) |  | YES  |   | 	 	| 
|T_SKBJ | varchar(100) |  | NO  |  	 |  	 |
|xn | char(4) |  | NO  |  	 |  	 |
|xq_id | char(1) |  | NO  |  	 |  	 |
|xf | decimal(18,1) |  | YES  |   | 	 	| 
|KCMC | varchar(100) |  | YES  |   | 	 	| 
 

## hlpdqdm
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|dqdm | varchar(6) |  | NO  |  	 |  	 |
|dqdm_1 | varchar(6) |  | YES  |   | 	 	| 
|dqmc | varchar(64) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## hlpxb
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|CODE | char(1) |  | NO  |  	 |  	 |
|NAMED | char(2) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## hlpxxlxdm
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|CODE | char(1) |  | NO  |  	 |  	 |
|NAMED | char(30) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_cj_format
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(2) |  | NO  |  	 |  	 |
|MC | varchar(50) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_cj_lessscoreinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XN | char(4) |  | NO  |  	 |  	 |
|XQ | char(1) |  | NO  |  	 |  	 |
|QDXN | varchar(4) |  | YES  |   | 	 	| 
|QDXQ | varchar(10) |  | YES  |   | 	 	| 
|XH | varchar(12) |  | NO  |  	 |  	 |
|KCDM | varchar(6) |  | NO  |  	 |  	 |
|XDLB | char(2) |  | YES  |   | 	 	| 
|KHFS_ID | char(2) |  | YES  |   | 	 	| 
|PDFS | char(2) |  | YES  |   | 	 	| 
|PSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|SYCJ | decimal(5,2) |  | YES  |   | 	 	| 
|QMCJ | decimal(5,2) |  | YES  |   | 	 	| 
|sjcj | decimal(5,2) |  | YES  |   | 	 	| 
|tlcj | decimal(5,2) |  | YES  |   | 	 	| 
|KSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|kscj1 | decimal(5,2) |  | YES  |   | 	 	| 
|BKCJ | decimal(5,2) |  | YES  |   | 	 	| 
|SJKSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|SJSJCJ | decimal(5,2) |  | YES  |   | 	 	| 
|YSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|JD | decimal(5,1) |  | YES  |   | 	 	| 
|XFJ | decimal(5,2) |  | YES  |   | 	 	| 
|zdjscj | decimal(5,2) |  | YES  |   | 	 	| 
|pyjscj | decimal(5,2) |  | YES  |   | 	 	| 
|dbzjcj | decimal(5,2) |  | YES  |   | 	 	| 
|kclb | char(2) |  | YES  |   | 	 	| 
|kclb2 | char(2) |  | YES  |   | 	 	| 
|kclb3 | char(2) |  | YES  |   | 	 	| 
|zxf | decimal(18,1) |  | YES  |   | 	 	| 
|gxf | decimal(18,1) |  | YES  |   | 	 	| 
|zxs | int(11) |  | YES  |   | 	 	| 
|BZ | varchar(50) |  | YES  |   | 	 	| 
|XKRQ | datetime | | YES  |  |    | 	 	 
|p_Flag | char(1) |  | YES  |   | 	 	| 
|BYLWMC | varchar(255) |  | YES  |   | 	 	| 
|BYSJBZ | char(1) |  | YES  |   | 	 	| 
|BYSJ | char(20) |  | YES  |   | 	 	| 
|sfcx | char(1) |  | YES  |   | 	 	| 
|LRCJFS | char(1) |  | YES  |   | 	 	| 
|flag_tmp | char(1) |  | YES  |   | 	 	| 
|kc_flag | char(1) |  | YES  |   | 	 	| 
|kcmc | varchar(50) |  | YES  |   | 	 	| 
|old_kcdm | char(6) |  | YES  |   | 	 	| 
|QZCJ | decimal(5,2) |  | YES  |   | 	 	| 
|bk_flag | char(1) |  | YES  |   | 	 	| 
|cxsf | decimal(5,2) |  | YES  |   | 	 	| 
|zs | int(11) |  | YES  |   | 	 	| 
|mx_flag | char(1) |  | YES  |   | 	 	| 
|stu_flag | char(2) |  | YES  |   | 	 	| 
|nj | char(4) |  | YES  |   | 	 	| 
|zy_id | char(4) |  | YES  |   | 	 	| 
|mxyy | varchar(50) |  | YES  |   | 	 	| 
|lsort2 | varchar(50) |  | YES  |   | 	 	| 
|lsort3 | varchar(50) |  | YES  |   | 	 	| 
|input_bz | char(1) |  | YES  |   | 	 	| 
|input_date	| datetime |  | YES  |   |   |  	 	 
|user_id | varchar(50) |  | YES  |   | 	 	| 
|sfqdcj | char(1) |  | YES  |   | 	 	| 
|input_code | bigint(20) |  | YES  |   | 	 	| 
|JNCJLB | varchar(2) |  | YES  |   | 	 	| 
|JNCJ_BXXS | varchar(2) |  | YES  |   | 	 	| 
|JNCJBFB | decimal(5,2) |  | YES  |   | 	 	| 
|JNCJ | decimal(5,2) |  | YES  |   | 	 	| 
|tsqkbj_m | char(2) |  | YES  |   | 	 	| 
|qdfs | char(2) |  | YES  |   | 	 	| 
|skfs | char(1) |  | YES  |   | 	 	| 
|jd_dj | char(2) |  | YES  |   | 	 	| 
|jycj | decimal(5,2) |  | YES  |   | 	 	| 
|cxhkflag | char(1) |  | YES  |   | 	 	| 
|jd_xgr | varchar(20) |  | YES  |   | 	 	| 
|jd_xgdate	| datetime |  | YES  |   |   |  	 	 
|jd_xgip | varchar(20) |  | YES  |   | 	 	| 
|PSCJ_BXXS | varchar(2) |  | YES  |   | 	 	| 
|qzCJ_BXXS | varchar(2) |  | YES  |   | 	 	| 
|qmCJ_BXXS | varchar(2) |  | YES  |   | 	 	| 
|kSCJ_BXXS | varchar(2) |  | YES  |   | 	 	| 
|tk_flag | char(1) |  | YES  |   | 	 	| 
|ysjd | decimal(5,1) |  | YES  |   | 	 	| 
|ysxfj | decimal(5,2) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_cj_lessscoreinfo_backup
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XN | char(4) |  | YES  |   | 	 	| 
|XQ | char(1) |  | YES  |   | 	 	| 
|QDXN | varchar(4) |  | YES  |   | 	 	| 
|QDXQ | char(10) |  | YES  |   | 	 	| 
|XH | varchar(12) |  | YES  |   | 	 	| 
|KCDM | varchar(6) |  | YES  |   | 	 	| 
|XDLB | char(2) |  | YES  |   | 	 	| 
|KHFS_ID | char(2) |  | YES  |   | 	 	| 
|PDFS | char(2) |  | YES  |   | 	 	| 
|PSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|SYCJ | decimal(5,2) |  | YES  |   | 	 	| 
|QMCJ | decimal(5,2) |  | YES  |   | 	 	| 
|sjcj | decimal(5,2) |  | YES  |   | 	 	| 
|tlcj | decimal(5,2) |  | YES  |   | 	 	| 
|KSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|kscj1 | decimal(5,2) |  | YES  |   | 	 	| 
|BKCJ | decimal(5,2) |  | YES  |   | 	 	| 
|SJKSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|SJSJCJ | decimal(5,2) |  | YES  |   | 	 	| 
|YSCJ | decimal(5,2) |  | YES  |   | 	 	| 
|JD | decimal(5,1) |  | YES  |   | 	 	| 
|XFJ | decimal(5,2) |  | YES  |   | 	 	| 
|zdjscj | decimal(5,2) |  | YES  |   | 	 	| 
|pyjscj | decimal(5,2) |  | YES  |   | 	 	| 
|dbzjcj | decimal(5,2) |  | YES  |   | 	 	| 
|kclb | char(2) |  | YES  |   | 	 	| 
|kclb2 | char(2) |  | YES  |   | 	 	| 
|kclb3 | char(2) |  | YES  |   | 	 	| 
|zxf | decimal(18,1) |  | YES  |   | 	 	| 
|gxf | decimal(18,1) |  | YES  |   | 	 	| 
|zxs | int(11) |  | YES  |   | 	 	| 
|BZ | varchar(50) |  | YES  |   | 	 	| 
|XKRQ	| datetime |  | YES  |   |   |  	 	 
|p_Flag | char(1) |  | YES  |   | 	 	| 
|BYLWMC | varchar(200) |  | YES  |   | 	 	| 
|BYSJBZ | char(1) |  | YES  |   | 	 	| 
|BYSJ | char(20) |  | YES  |   | 	 	| 
|sfcx | char(1) |  | YES  |   | 	 	| 
|LRCJFS | char(1) |  | YES  |   | 	 	| 
|flag_tmp | char(1) |  | YES  |   | 	 	| 
|kc_flag | char(1) |  | YES  |   | 	 	| 
|kcmc | varchar(50) |  | YES  |   | 	 	| 
|old_kcdm | char(6) |  | YES  |   | 	 	| 
|QZCJ | decimal(5,2) |  | YES  |   | 	 	| 
|bk_flag | char(1) |  | YES  |   | 	 	| 
|cxsf | decimal(5,2) |  | YES  |   | 	 	| 
|zs | int(11) |  | YES  |   | 	 	| 
|mx_flag | char(1) |  | YES  |   | 	 	| 
|stu_flag | char(2) |  | YES  |   | 	 	| 
|nj | char(4) |  | YES  |   | 	 	| 
|zy_id | char(4) |  | YES  |   | 	 	| 
|mxyy | varchar(50) |  | YES  |   | 	 	| 
|lsort2 | varchar(50) |  | YES  |   | 	 	| 
|lsort3 | varchar(50) |  | YES  |   | 	 	| 
|input_bz | char(1) |  | YES  |   | 	 	| 
|input_date	| datetime | | YES  |   | 	 	|  	 
|user_id | varchar(50) |  | YES  |   | 	 	| 
|sfqdcj | char(1) |  | YES  |   | 	 	| 
|input_code | bigint(20) |  | YES  |   | 	 	| 
|JNCJLB | varchar(2) |  | YES  |   | 	 	| 
|JNCJ_BXXS | varchar(2) |  | YES  |   | 	 	| 
|JNCJBFB | decimal(5,2) |  | YES  |   | 	 	| 
|JNCJ | decimal(5,2) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_cj_levelsort
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(10) |  | NO  |  	 |  	 |
|Value | decimal(5,2) |  | YES  |   | 	 	| 
|Text | varchar(10) |  | YES  |   | 	 	| 
|english | varchar(100) |  | YES  |   | 	 	| 
|LB | varchar(2) |  | YES  |   | 	 	| 
|sx | decimal(5,2) |  | YES  |   | 	 	| 
|xx | decimal(5,2) |  | YES  |   | 	 	| 
|jd | decimal(3,1) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|user_v | decimal(5,2) |  | YES  |   | 	 	| 
|rate | decimal(5,1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_jh_lsort1info
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | char(2) |  | NO  |  	 |  	 |
|MC | varchar(20) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|JC | varchar(20) |  | YES  |   | 	 	| 
|english | varchar(100) |  | YES  |   | 	 	| 
|YWJC | varchar(10) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_jh_setlessoninfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|ZY_FLAG | char(1) |  | YES  |   | 	 	| 
|DM | char(6) |  | NO  |  	 |  	 |
|QYKCDM | char(9) |  | YES  |   | 	 	| 
|ZWMC | varchar(255) |  | YES  |   | 	 	| 
|ZWJC | varchar(255) |  | YES  |   | 	 	| 
|YWMC | varchar(255) |  | YES  |   | 	 	| 
|YWJC | varchar(255) |  | YES  |   | 	 	| 
|CDDW_ID | varchar(4) |  | YES  |   | 	 	| 
|ZXF | decimal(3,1) |  | YES  |   | 	 	| 
|ZXS | decimal(5,1) |  | YES  |   | 	 	| 
|SYXS | int(11) |  | YES  |   | 	 	| 
|XXKC | varchar(254) |  | YES  |   | 	 	| 
|LRJJ | longtext |	 	  | YES  | |   |  	 	 
|SYZY | varchar(100) |  | YES  |   | 	 	| 
|CKJC | varchar(200) |  | YES  |   | 	 	| 
|ZGR | char(8) |  | YES  |   | 	 	| 
|CBDW | varchar(2) |  | YES  |   | 	 	| 
|YS | int(11) |  | YES  |   | 	 	| 
|DJ | decimal(5,1) |  | YES  |   | 	 	| 
|ZB | char(10) |  | YES  |   | 	 	| 
|SHR | char(10) |  | YES  |   | 	 	| 
|kclb | char(2) |  | YES  |   | 	 	| 
|sjlb | char(2) |  | YES  |   | 	 	| 
|sxlb | char(4) |  | YES  |   | 	 	| 
|sjxs | int(11) |  | YES  |   | 	 	| 
|qtxs | int(11) |  | YES  |   | 	 	| 
|p_flag | char(1) |  | YES  |   | 	 	| 
|user_kcid | char(10) |  | YES  |   | 	 	| 
|xsfpxl | varchar(50) |  | YES  |   | 	 	| 
|kcz | char(4) |  | YES  |   | 	 	| 
|bycz_flag | varchar(1) |  | YES  |   | 	 	| 
|ljdz | varchar(100) |  | YES  |   | 	 	| 
|pycc | varchar(6) |  | YES  |   | 	 	| 
|xk | varchar(10) |  | YES  |   | 	 	| 
|jys | varchar(5) |  | YES  |   | 	 	| 
|JPKCLB | varchar(2) |  | YES  |   | 	 	| 
|QXHZKFKC | char(1) |  | YES  |   | 	 	| 
|ZYKSSJXM | longtext |	 	  | YES  | |   |  	 	 
|lb1_id | char(2) |  | YES  |   | 	 	| 
|lb2_id | char(2) |  | YES  |   | 	 	| 
|jswhcj | char(1) |  | YES  |   | 	 	| 
|cjgc_FLAG | char(1) |  | YES  |   | 	 	| 
|ZHBXXS | varchar(2) |  | YES  |   | 	 	| 
|PSBXXS | varchar(2) |  | YES  |   | 	 	| 
|PSBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QZBXXS | varchar(2) |  | YES  |   | 	 	| 
|QZBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QMBXXS | varchar(2) |  | YES  |   | 	 	| 
|QMBFB | decimal(5,2) |  | YES  |   | 	 	| 
|KBLB | varchar(2) |  | YES  |   | 	 	| 
|JNCJLB | varchar(2) |  | YES  |   | 	 	| 
|JNCJBXXS | varchar(2) |  | YES  |   | 	 	| 
|JNCJBFB | decimal(5,2) |  | YES  |   | 	 	| 
|kscj01 | decimal(5,2) |  | YES  |   | 	 	| 
|kscj02 | decimal(5,2) |  | YES  |   | 	 	| 
|yxl | decimal(5,4) |  | YES  |   | 	 	| 
|SYFX | varchar(50) |  | YES  |   | 	 	| 
|sxgz | varchar(10) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_jh_setlessoninfo_temp_afterdelete
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|ZY_FLAG | char(1) |  | YES  |   | 	 	| 
|DM | char(6) |  | YES  |   | 	 	| 
|QYKCDM | char(9) |  | YES  |   | 	 	| 
|ZWMC | varchar(255) |  | YES  |   | 	 	| 
|ZWJC | varchar(255) |  | YES  |   | 	 	| 
|YWMC | varchar(255) |  | YES  |   | 	 	| 
|YWJC | varchar(255) |  | YES  |   | 	 	| 
|CDDW_ID | char(4) |  | YES  |   | 	 	| 
|ZXF | decimal(18,0) |  | YES  |   | 	 	| 
|ZXS | decimal(18,0) |  | YES  |   | 	 	| 
|SYXS | int(11) |  | YES  |   | 	 	| 
|XXKC | varchar(254) |  | YES  |   | 	 	| 
|LRJJ | longtext |	 	  | YES  | |   |  	 	 
|SYZY | varchar(100) |  | YES  |   | 	 	| 
|CKJC | varchar(200) |  | YES  |   | 	 	| 
|ZGR | char(8) |  | YES  |   | 	 	| 
|CBDW | varchar(50) |  | YES  |   | 	 	| 
|YS | int(11) |  | YES  |   | 	 	| 
|DJ | decimal(18,0) |  | YES  |   | 	 	| 
|ZB | char(10) |  | YES  |   | 	 	| 
|SHR | char(10) |  | YES  |   | 	 	| 
|kclb | char(2) |  | YES  |   | 	 	| 
|sjlb | char(2) |  | YES  |   | 	 	| 
|sxlb | char(4) |  | YES  |   | 	 	| 
|sjxs | int(11) |  | YES  |   | 	 	| 
|qtxs | int(11) |  | YES  |   | 	 	| 
|p_flag | char(1) |  | YES  |   | 	 	| 
|user_kcid | char(10) |  | YES  |   | 	 	| 
|xsfpxl | varchar(50) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_jh_terminfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | char(1) |  | NO  |  	 |  	 |
|MC | varchar(20) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_auto_table
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|KC_FLAG | char(1) |  | YES  |   | 	 	| 
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|SKBJ | varchar(12) |  | NO  |  	 |  	 |
|NJ | char(4) |  | YES  |   | 	 	| 
|BJDM | char(20) |  | NO  |  	 |  	 |
|KCID | char(8) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|T_JS | int(11) |  | YES  |   | 	 	| 
|CDDW_ID | char(4) |  | YES  |   | 	 	| 
|JCInfo | varchar(50) |  | YES  |   | 	 	| 
|JCz | char(10) |  | NO  |  	 |  	 |
|ZC | varchar(50) |  | YES  |   | 	 	| 
|JS | char(14) |  | YES  |   | 	 	| 
|KSZ | int(11) |  | YES  |   | 	 	| 
|JSZ | int(11) |  | YES  |   | 	 	| 
|DSZ | char(1) |  | NO  |  	 |  	 |
|JXL | char(3) |  | YES  |   | 	 	| 
|JSM | char(20) |  | NO  |  	 |  	 |
|JSLX | char(2) |  | YES  |   | 	 	| 
|SKBJ_RS | int(11) |  | YES  |   | 	 	| 
|SKBJ_BS | int(11) |  | YES  |   | 	 	| 
|KB_NULL | char(10) |  | YES  |   | 	 	| 
|stimezc | varchar(50) |  | NO  |  	 |  	 |
|T_HBSK | int(11) |  | YES  |   | 	 	| 
|Analyse | varchar(200) |  | YES  |   | 	 	| 
|JCAnalyse | varchar(50) |  | YES  |   | 	 	| 
|ZHANGYANG | char(100) |  | YES  |   | 	 	| 
|zhub | char(10) |  | YES  |   | 	 	| 
|TK_FLAG | char(1) |  | YES  |   | 	 	| 
|TK_CDTATE	| datetime |  | YES  |   |   |  	 	 
|TK_JCZ | char(3) |  | YES  |   | 	 	| 
|TK_DSZ | char(1) |  | YES  |   | 	 	| 
|TK_JSM | char(20) |  | YES  |   | 	 	| 
|TK_ZJJS | char(14) |  | YES  |   | 	 	| 
|TK_STIMEZC | varchar(50) |  | YES  |   | 	 	| 
|TK_JCIF | varchar(50) |  | YES  |   | 	 	| 
|TK_JS | int(11) |  | YES  |   | 	 	| 
|sffzxk | varchar(50) |  | YES  |   | 	 	| 
|sffxzsk | char(10) |  | YES  |   | 	 	| 
|tingk_flag | char(1) |  | YES  |   | 	 	| 
|t_cjjs1 | char(10) |  | YES  |   | 	 	| 
|bjkb_null | char(1) |  | YES  |   | 	 	| 
|jskb_null | char(1) |  | YES  |   | 	 	| 
|jsmkb_null | char(1) |  | YES  |   | 	 	| 
|kckb_null | char(1) |  | YES  |   | 	 	| 
|tkyy | varchar(100) |  | YES  |   | 	 	| 
|tingkyy | varchar(100) |  | YES  |   | 	 	| 
|ClassGroup | varchar(4) |  | NO  |  	 |  	 |
|JSM_XQ | varchar(2) |  | YES  |   | 	 	| 
|Time_Begin	| datetime |  | YES  |   |   |  	 	 
|Time_End	| datetime |  | YES  |   |   |  	 	 
|JCZ_All | varchar(21) |  | YES  |   | 	 	| 
|jxjdbxh | int(11) |  | YES  |   | 	 	| 
|skbjxh | int(11) |  | YES  |   | 	 	| 
|jbr | varchar(50) |  | YES  |   | 	 	| 
|xs | decimal(5,2) |  | YES  |   | 	 	| 
|tkyy_bz | varchar(100) |  | YES  |   | 	 	| 
|tingkyy_bz | varchar(100) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_auto_table_deleted
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|KC_FLAG | char(1) |  | YES  |   | 	 	| 
|XN | char(4) |  | YES  |   | 	 	| 
|XQ_ID | char(2) |  | YES  |   | 	 	| 
|SKBJ | varchar(12) |  | YES  |   | 	 	| 
|NJ | char(4) |  | YES  |   | 	 	| 
|BJDM | char(20) |  | YES  |   | 	 	| 
|KCID | char(8) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|T_JS | int(11) |  | YES  |   | 	 	| 
|CDDW_ID | char(4) |  | YES  |   | 	 	| 
|JCInfo | varchar(50) |  | YES  |   | 	 	| 
|JCz | char(10) |  | YES  |   | 	 	| 
|ZC | varchar(50) |  | YES  |   | 	 	| 
|JS | char(14) |  | YES  |   | 	 	| 
|KSZ | int(11) |  | YES  |   | 	 	| 
|JSZ | int(11) |  | YES  |   | 	 	| 
|DSZ | char(1) |  | YES  |   | 	 	| 
|JXL | char(3) |  | YES  |   | 	 	| 
|JSM | char(20) |  | YES  |   | 	 	| 
|JSLX | char(2) |  | YES  |   | 	 	| 
|SKBJ_RS | int(11) |  | YES  |   | 	 	| 
|SKBJ_BS | int(11) |  | YES  |   | 	 	| 
|KB_NULL | char(10) |  | YES  |   | 	 	| 
|stimezc | varchar(50) |  | YES  |   | 	 	| 
|T_HBSK | int(11) |  | YES  |   | 	 	| 
|Analyse | varchar(200) |  | YES  |   | 	 	| 
|JCAnalyse | varchar(50) |  | YES  |   | 	 	| 
|ZHANGYANG | char(100) |  | YES  |   | 	 	| 
|zhub | char(10) |  | YES  |   | 	 	| 
|TK_FLAG | char(1) |  | YES  |   | 	 	| 
|TK_CDTATE	| datetime |  | YES  |   |   |  	 	 
|TK_JCZ | char(3) |  | YES  |   | 	 	| 
|TK_DSZ | char(1) |  | YES  |   | 	 	| 
|TK_JSM | char(20) |  | YES  |   | 	 	| 
|TK_ZJJS | char(14) |  | YES  |   | 	 	| 
|TK_STIMEZC | varchar(50) |  | YES  |   | 	 	| 
|TK_JCIF | varchar(50) |  | YES  |   | 	 	| 
|TK_JS | int(11) |  | YES  |   | 	 	| 
|sffzxk | varchar(50) |  | YES  |   | 	 	| 
|sffxzsk | char(10) |  | YES  |   | 	 	| 
|tingk_flag | char(1) |  | YES  |   | 	 	| 
|t_cjjs1 | char(10) |  | YES  |   | 	 	| 
|ClassGroup | varchar(4) |  | YES  |   | 	 	| 
|jbr | varchar(50) |  | YES  |   | 	 	| 
|xs | decimal(5,2) |  | YES  |   | 	 	| 
|tkyy_bz | varchar(100) |  | YES  |   | 	 	| 
|tingkyy_bz | varchar(100) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_auto_table_his
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|KC_FLAG | char(1) |  | YES  |   | 	 	| 
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|SKBJ | varchar(12) |  | NO  |  	 |  	 |
|NJ | char(4) |  | YES  |   | 	 	| 
|BJDM | char(20) |  | NO  |  	 |  	 |
|KCID | char(8) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|T_JS | int(11) |  | YES  |   | 	 	| 
|CDDW_ID | char(4) |  | YES  |   | 	 	| 
|JCInfo | varchar(50) |  | YES  |   | 	 	| 
|JCz | char(10) |  | NO  |  	 |  	 |
|ZC | varchar(50) |  | YES  |   | 	 	| 
|JS | char(14) |  | YES  |   | 	 	| 
|KSZ | int(11) |  | YES  |   | 	 	| 
|JSZ | int(11) |  | YES  |   | 	 	| 
|DSZ | char(1) |  | NO  |  	 |  	 |
|JXL | char(3) |  | YES  |   | 	 	| 
|JSM | char(20) |  | NO  |  	 |  	 |
|JSLX | char(2) |  | YES  |   | 	 	| 
|SKBJ_RS | int(11) |  | YES  |   | 	 	| 
|SKBJ_BS | int(11) |  | YES  |   | 	 	| 
|KB_NULL | char(10) |  | YES  |   | 	 	| 
|stimezc | varchar(50) |  | NO  |  	 |  	 |
|T_HBSK | int(11) |  | YES  |   | 	 	| 
|Analyse | varchar(200) |  | YES  |   | 	 	| 
|JCAnalyse | varchar(50) |  | YES  |   | 	 	| 
|ZHANGYANG | char(100) |  | YES  |   | 	 	| 
|zhub | char(10) |  | YES  |   | 	 	| 
|TK_FLAG | char(1) |  | YES  |   | 	 	| 
|TK_CDTATE	| datetime |  | YES  |   |   |  	 	 
|TK_JCZ | char(3) |  | YES  |   | 	 	| 
|TK_DSZ | char(1) |  | YES  |   | 	 	| 
|TK_JSM | char(20) |  | YES  |   | 	 	| 
|TK_ZJJS | char(14) |  | YES  |   | 	 	| 
|TK_STIMEZC | varchar(50) |  | YES  |   | 	 	| 
|TK_JCIF | varchar(50) |  | YES  |   | 	 	| 
|TK_JS | int(11) |  | YES  |   | 	 	| 
|sffzxk | varchar(50) |  | YES  |   | 	 	| 
|sffxzsk | char(10) |  | YES  |   | 	 	| 
|tingk_flag | char(1) |  | YES  |   | 	 	| 
|t_cjjs1 | char(10) |  | YES  |   | 	 	| 
|bjkb_null | char(1) |  | YES  |   | 	 	| 
|jskb_null | char(1) |  | YES  |   | 	 	| 
|jsmkb_null | char(1) |  | YES  |   | 	 	| 
|kckb_null | char(1) |  | YES  |   | 	 	| 
|tkyy | varchar(100) |  | YES  |   | 	 	| 
|tingkyy | varchar(100) |  | YES  |   | 	 	| 
|ClassGroup | varchar(4) |  | NO  |  	 |  	 |
|JSM_XQ | varchar(2) |  | YES  |   | 	 	| 
|Time_Begin	| datetime |  | YES  |   |   |  	 	 
|Time_End	| datetime |  | YES  |   |   |  	 	 
|JCZ_All | varchar(21) |  | YES  |   | 	 	| 
|jxjdbxh | int(11) |  | YES  |   | 	 	| 
|skbjxh | int(11) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_auto_table_tkrecord
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|KC_FLAG | char(1) |  | YES  |   | 	 	| 
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(2) |  | NO  |  	 |  	 |
|SKBJ | varchar(12) |  | NO  |  	 |  	 |
|NJ | char(4) |  | YES  |   | 	 	| 
|BJDM | char(20) |  | NO  |  	 |  	 |
|KCID | char(8) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|T_JS | int(11) |  | YES  |   | 	 	| 
|CDDW_ID | char(4) |  | YES  |   | 	 	| 
|JCInfo | varchar(50) |  | YES  |   | 	 	| 
|JCz | char(10) |  | NO  |  	 |  	 |
|ZC | varchar(50) |  | YES  |   | 	 	| 
|JS | char(14) |  | YES  |   | 	 	| 
|KSZ | int(11) |  | YES  |   | 	 	| 
|JSZ | int(11) |  | YES  |   | 	 	| 
|DSZ | char(1) |  | NO  |  	 |  	 |
|JXL | char(3) |  | YES  |   | 	 	| 
|JSM | char(20) |  | YES  |   | 	 	| 
|JSLX | char(2) |  | YES  |   | 	 	| 
|SKBJ_RS | int(11) |  | YES  |   | 	 	| 
|SKBJ_BS | int(11) |  | YES  |   | 	 	| 
|KB_NULL | char(10) |  | YES  |   | 	 	| 
|stimezc | varchar(50) |  | NO  |  	 |  	 |
|T_HBSK | int(11) |  | YES  |   | 	 	| 
|Analyse | varchar(200) |  | YES  |   | 	 	| 
|JCAnalyse | varchar(50) |  | YES  |   | 	 	| 
|ZHANGYANG | char(100) |  | YES  |   | 	 	| 
|zhub | char(10) |  | YES  |   | 	 	| 
|TK_FLAG | char(1) |  | YES  |   | 	 	| 
|TK_CDTATE	| datetime |  | YES  |   |   |  	 	 
|TK_JCZ | char(3) |  | YES  |   | 	 	| 
|TK_DSZ | char(1) |  | YES  |   | 	 	| 
|TK_JSM | char(20) |  | YES  |   | 	 	| 
|TK_ZJJS | char(14) |  | YES  |   | 	 	| 
|TK_STIMEZC | varchar(50) |  | YES  |   | 	 	| 
|TK_JCIF | varchar(50) |  | YES  |   | 	 	| 
|TK_JS | int(11) |  | YES  |   | 	 	| 
|sffzxk | varchar(50) |  | YES  |   | 	 	| 
|sffxzsk | char(10) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_plan
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XH | int(11) |  | NO  |  是	 | 	 |
|KCID | varchar(8) |  | NO  |  	 |  	 |
|KC_ID | varchar(6) |  | YES  |   | 	 	| 
|KCMC | varchar(100) |  | YES  |   | 	 	| 
|CDDW_ID | varchar(4) |  | YES  |   | 	 	| 
|ZY_ID | char(4) |  | NO  |  	 |  	 |
|NJ | char(4) |  | NO  |  	 |  	 |
|PYCC_ID | char(10) |  | YES  |   | 	 	| 
|PYLB_ID | char(10) |  | YES  |   | 	 	| 
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|ZXS | int(11) |  | YES  |   | 	 	| 
|XF | decimal(18,1) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|SYXS | int(11) |  | YES  |   | 	 	| 
|SJXS | int(11) |  | YES  |   | 	 	| 
|QTXS | int(11) |  | YES  |   | 	 	| 
|KCLB | char(2) |  | YES  |   | 	 	| 
|KHFS | varchar(2) |  | YES  |   | 	 	| 
|JKKSZ | int(11) |  | YES  |   | 	 	| 
|JKJSZ | int(11) |  | YES  |   | 	 	| 
|stimezc | varchar(50) |  | YES  |   | 	 	| 
|sxh | char(1) |  | YES  |   | 	 	| 
|kclb2 | char(2) |  | YES  |   | 	 	| 
|kclb3 | char(2) |  | YES  |   | 	 	| 
|sskqz | char(6) |  | YES  |   | 	 	| 
|zs | decimal(9,1) |  | YES  |   | 	 	| 
|bz | varchar(50) |  | YES  |   | 	 	| 
|kc_flag | char(1) |  | YES  |   | 	 	| 
|modify_type | char(10) |  | YES  |   | 	 	| 
|user_kcid | char(10) |  | YES  |   | 	 	| 
|xxkc_flag | char(1) |  | YES  |   | 	 	| 
|QYJS_FLAG | char(2) |  | YES  |   | 	 	| 
|zx_flag | char(1) |  | YES  |   | 	 	| 
|fx_flag | char(1) |  | YES  |   | 	 	| 
|zfx_flag | char(1) |  | YES  |   | 	 	| 
|bz_fx | varchar(50) |  | YES  |   | 	 	| 
|modify_type_fx | char(10) |  | YES  |   | 	 	| 
|kcdw | varchar(2) |  | YES  |   | 	 	| 
|zyfx | varchar(210) |  | YES  |   | 	 	| 
|yx_flag | char(1) |  | YES  |   | 	 	| 
|xfx_flag | char(1) |  | YES  |   | 	 	| 
|xsxw_flag | char(1) |  | YES  |   | 	 	| 
|bgyy | varchar(100) |  | YES  |   | 	 	| 
|KCLB_XK | varchar(10) |  | YES  |   | 	 	| 
|xw_flag | char(1) |  | YES  |   | 	 	| 
|BJ_FLAG | char(1) |  | YES  |   | 	 	| 
|cjgc_FLAG | varchar(1) |  | YES  |   | 	 	| 
|ZHBXXS | varchar(2) |  | YES  |   | 	 	| 
|PSBXXS | varchar(2) |  | YES  |   | 	 	| 
|PSBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QZBXXS | varchar(2) |  | YES  |   | 	 	| 
|QZBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QMBXXS | varchar(2) |  | YES  |   | 	 	| 
|QMBFB | decimal(5,2) |  | YES  |   | 	 	| 
|KBLB | varchar(2) |  | YES  |   | 	 	| 
|JNCJLB | varchar(2) |  | YES  |   | 	 	| 
|JNCJBXXS | varchar(2) |  | YES  |   | 	 	| 
|JNCJBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QT_FLAG | varchar(1) |  | YES  |   | 	 	| 
|QT_CJBXXS | varchar(2) |  | YES  |   | 	 	| 
|QT_CJBXXS_TJ | decimal(5,2) |  | YES  |   | 	 	| 
|QT_ZHBXXS | varchar(2) |  | YES  |   | 	 	| 
|QT_PSBXXS | varchar(2) |  | YES  |   | 	 	| 
|QT_PSBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QT_QZBXXS | varchar(2) |  | YES  |   | 	 	| 
|QT_QZBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QT_QMBXXS | varchar(2) |  | YES  |   | 	 	| 
|QT_QMBFB | decimal(5,2) |  | YES  |   | 	 	| 
|QT_JNCJLB | varchar(2) |  | YES  |   | 	 	| 
|QT_JNBXXS | varchar(2) |  | YES  |   | 	 	| 
|QT_JNBFB | decimal(5,2) |  | YES  |   | 	 	| 
|dsz | char(1) |  | YES  |   | 	 	| 
|T_JS | int(11) |  | YES  |   | 	 	| 
|kc_flag_rw | char(2) |  | YES  |   | 	 	| 
|skbj_bS | int(11) |  | YES  |   | 	 	| 
|T_RS | int(11) |  | YES  |   | 	 	| 
|KCLB_rw | char(2) |  | YES  |   | 	 	| 
|KCLB2_rw | char(2) |  | YES  |   | 	 	| 
|KHFS_rw | char(2) |  | YES  |   | 	 	| 
|zzxs_rw | int(11) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_plan_audit
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|NJ | char(4) |  | NO  |  	 |  	 |
|ZY_ID | char(4) |  | NO  |  	 |  	 |
|KC_COUNT | int(11) |  | YES  |   | 	 	| 
|HJ_COUNT | int(11) |  | YES  |   | 	 	| 
|ZT_FLAG | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_plan_before
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XH | varchar(12) |  | NO  |  	 |  	 |
|KCID | varchar(8) |  | NO  |  	 |  	 |
|ZY_ID | char(4) |  | YES  |   | 	 	| 
|NJ | char(4) |  | YES  |   | 	 	| 
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|kc_flag | char(1) |  | YES  |   | 	 	| 
|kclb | varchar(2) |  | YES  |   | 	 	| 
|kclb2 | varchar(2) |  | YES  |   | 	 	| 
|ZXS | int(11) |  | YES  |   | 	 	| 
|XF | decimal(18,1) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|SYXS | int(11) |  | YES  |   | 	 	| 
|SJXS | int(11) |  | YES  |   | 	 	| 
|QTXS | int(11) |  | YES  |   | 	 	| 
|ydlb | varchar(2) |  | YES  |   | 	 	| 
|KHFS | varchar(2) |  | YES  |   | 	 	| 
|setdate	| datetime |  | YES  |   |   |  	 	 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_plan_practice
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XH | int(11) |  | YES  |   | 	 	| 
|KCID | varchar(8) |  | YES  |   | 	 	| 
|KC_ID | varchar(6) |  | YES  |   | 	 	| 
|KCMC | varchar(100) |  | YES  |   | 	 	| 
|CDDW_ID | char(4) |  | YES  |   | 	 	| 
|ZY_ID | char(4) |  | YES  |   | 	 	| 
|NJ | char(4) |  | YES  |   | 	 	| 
|PYCC_ID | char(10) |  | YES  |   | 	 	| 
|PYLB_ID | char(10) |  | YES  |   | 	 	| 
|XN | char(4) |  | YES  |   | 	 	| 
|XQ_ID | char(1) |  | YES  |   | 	 	| 
|ZXS | int(11) |  | YES  |   | 	 	| 
|XF | decimal(18,1) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|SYXS | int(11) |  | YES  |   | 	 	| 
|SJXS | int(11) |  | YES  |   | 	 	| 
|QTXS | int(11) |  | YES  |   | 	 	| 
|KCLB | char(2) |  | YES  |   | 	 	| 
|KHFS | char(10) |  | YES  |   | 	 	| 
|JKKSZ | int(11) |  | YES  |   | 	 	| 
|JKJSZ | int(11) |  | YES  |   | 	 	| 
|stimezc | varchar(50) |  | YES  |   | 	 	| 
|sxh | char(1) |  | YES  |   | 	 	| 
|zs | varchar(50) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_plan_process
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|NJ | char(4) |  | NO  |  	 |  	 |
|ZY_ID | char(4) |  | NO  |  	 |  	 |
|KCID | char(6) |  | NO  |  	 |  	 |
|ZC | int(11) |  | NO  |  	 |  	 |
|JSXS | int(11) |  | YES  |   | 	 	| 
|JSNR | varchar(512) |  | YES  |   | 	 	| 
|SKFS | varchar(2) |  | YES  |   | 	 	| 
|JSLX | varchar(2) |  | YES  |   | 	 	| 
|LSJS | int(11) |  | YES  |   | 	 	| 
|SYXS | int(11) |  | YES  |   | 	 	| 
|SYNR | varchar(512) |  | YES  |   | 	 	| 
|SY_SKFS | varchar(2) |  | YES  |   | 	 	| 
|SY_JSLX | varchar(2) |  | YES  |   | 	 	| 
|SY_LSJS | int(11) |  | YES  |   | 	 	| 
|memo | varchar(100) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_plancount
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XN | char(4) |  | YES  |   | 	 	| 
|XQ_ID | char(2) |  | YES  |   | 	 	| 
|KCID | char(10) |  | YES  |   | 	 	| 
|KCLB | char(2) |  | YES  |   | 	 	| 
|XF | decimal(18,1) |  | YES  |   | 	 	| 
|KKNJ | varchar(50) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_planskrs
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XN | char(4) |  | YES  |   | 	 	| 
|XQ_ID | char(2) |  | YES  |   | 	 	| 
|JCz | char(10) |  | YES  |   | 	 	| 
|Analyse | varchar(200) |  | YES  |   | 	 	| 
|NJ | char(4) |  | YES  |   | 	 	| 
|YX_ID | char(2) |  | YES  |   | 	 	| 
|xsrs | int(11) |  | YES  |   | 	 	| 
|schoolarea | varchar(10) |  | YES  |   | 	 	| 
|skrs | int(11) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_selkc
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|CXXN | char(4) |  | YES  |   | 	 	| 
|CXXQ_ID | char(1) |  | YES  |   | 	 	| 
|XKCXbz | char(1) |  | YES  |   | 	 	| 
|xn | varchar(4) |  | NO  |  	 |  	 |
|xq_id | char(1) |  | NO  |  	 |  	 |
|XS_ID | varchar(20) |  | NO  |  	 |  	 |
|KC_ID | varchar(10) |  | NO  |  	 |  	 |
|kcid | char(10) |  | YES  |   | 	 	| 
|NJ | char(4) |  | YES  |   | 	 	| 
|T_ZJJS | char(10) |  | YES  |   | 	 	| 
|ZY_ID | varchar(10) |  | YES  |   | 	 	| 
|BJ_ID | varchar(20) |  | YES  |   | 	 	| 
|State | char(1) |  | YES  |   | 	 	| 
|Memo | varchar(50) |  | YES  |   | 	 	| 
|CDate	| datetime |  | YES  |   |   |  	 	 
|Tj | char(1) |  | YES  |   | 	 	| 
|kclb | char(2) |  | YES  |   | 	 	| 
|kclb2 | char(2) |  | YES  |   | 	 	| 
|jszxrl | decimal(18,0) |  | YES  |   | 	 	| 
|KC_FLAG | char(1) |  | YES  |   | 	 	| 
|KHFS | char(2) |  | YES  |   | 	 	| 
|xklb | char(1) |  | YES  |   | 	 	| 
|IP | varchar(100) |  | YES  |   | 	 	| 
|XF | decimal(5,0) |  | YES  |   | 	 	| 
|ZXS | decimal(5,2) |  | YES  |   | 	 	| 
|CDDW_ID | varchar(10) |  | YES  |   | 	 	| 
|KHFS_ID | varchar(2) |  | YES  |   | 	 	| 
|Stu_flag | char(1) |  | YES  |   | 	 	| 
|qt_flag | char(1) |  | YES  |   | 	 	| 
|syxs | decimal(18,0) |  | YES  |   | 	 	| 
|sjxs | decimal(18,0) |  | YES  |   | 	 	| 
|qtxs | decimal(18,0) |  | YES  |   | 	 	| 
|StuSys_flag | char(1) |  | YES  |   | 	 	| 
|zzxs | decimal(18,0) |  | YES  |   | 	 	| 
|yxtj | char(1) |  | YES  |   | 	 	| 
|cxcxflag | char(2) |  | YES  |   | 	 	| 
|qyjsflag | char(2) |  | YES  |   | 	 	| 
|skbj_group | varchar(12) |  | YES  |   | 	 	| 
|xyjc | char(1) |  | YES  |   | 	 	| 
|ContentID | char(8) |  | YES  |   | 	 	| 
|sfpk | char(1) |  | YES  |   | 	 	| 
|LockFlag | char(1) |  | YES  |   | 	 	| 
|sfzx | char(1) |  | YES  |   | 	 	| 
|xjzt | char(2) |  | YES  |   | 	 	| 
|cjlrr | varchar(10) |  | YES  |   | 	 	| 
|wblb | varchar(4) |  | YES  |   | 	 	| 
|kcbk | varchar(4) |  | YES  |   | 	 	| 
|hkbk | varchar(4) |  | YES  |   | 	 	| 
|wap_area_xx	| datetime |  | YES  |   |   |  	 	 
|wap_area_sx	| datetime |  | YES  |   |   |  	 	 
|wap_area_ps_xx	| datetime |  | YES  |   |   |  	 	 
|wap_area_ps_sx	| datetime |  | YES  |   |   |  	 	 
|wap_area_qz_xx	| datetime |  | YES  |   |   |  	 	 
|wap_area_qz_sx	| datetime |  | YES  |   |   |  	 	 
|wap_area_jn_xx	| datetime |  | YES  |   |   |  	 	 
|wap_area_jn_sx	| datetime |  | YES  |   |   |  	 	 
|y_kcid | char(6) |  | YES  |   | 	 	| 
|sh_flag | char(1) |  | YES  |   | 	 	| 
|tbtk_kcid | char(6) |  | YES  |   | 	 	| 
|tbtk_skbj | varchar(12) |  | YES  |   | 	 	| 
|tbtk_shflag | char(1) |  | YES  |   | 	 	| 
|y_skbj | varchar(12) |  | YES  |   | 	 	| 
|kclb3 | char(2) |  | YES  |   | 	 	| 
|kclb_xk | varchar(10) |  | YES  |   | 	 	| 
|ctbl | varchar(10) |  | YES  |   | 	 	| 
|xfxf | decimal(10,2) |  | YES  |   | 	 	| 
|sfszcjlrr | char(1) |  | YES  |   | 	 	| 
|cxmtflag | varchar(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kb_task
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XH | int(11) |  | NO  |  	是 | 	 |
|KC_FLAG | char(1) |  | YES  |   | 	 	| 
|KCID | varchar(8) |  | YES  |   | 	 	| 
|KC_ID | varchar(6) |  | YES  |   | 	 	| 
|KCMC | varchar(100) |  | YES  |   | 	 	| 
|CDDW_ID | varchar(4) |  | YES  |   | 	 	| 
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|XQ | char(10) |  | YES  |   | 	 	| 
|PYLB_ID | char(10) |  | YES  |   | 	 	| 
|PYCC_ID | char(10) |  | YES  |   | 	 	| 
|NJ | char(4) |  | YES  |   | 	 	| 
|ZY_ID | char(4) |  | YES  |   | 	 	| 
|ZXS | int(11) |  | YES  |   | 	 	| 
|XF | decimal(18,1) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|SYXS | int(11) |  | YES  |   | 	 	| 
|SJXS | int(11) |  | YES  |   | 	 	| 
|QTXS | int(11) |  | YES  |   | 	 	| 
|KCLB | char(2) |  | YES  |   | 	 	| 
|KHFS | varchar(2) |  | YES  |   | 	 	| 
|JKKSZ | int(11) |  | YES  |   | 	 	| 
|JKJSZ | int(11) |  | YES  |   | 	 	| 
|T_ZJJS | char(10) |  | YES  |   | 	 	| 
|T_CJJS1 | char(10) |  | YES  |   | 	 	| 
|T_CJJS2 | char(10) |  | YES  |   | 	 	| 
|T_CJJS3 | char(10) |  | YES  |   | 	 	| 
|T_SKBJ | varchar(100) |  | NO  |  	 |  	 |
|T_RS | int(11) |  | YES  |   | 	 	| 
|T_BS | int(11) |  | YES  |   | 	 	| 
|PKMS | char(1) |  | YES  |   | 	 	| 
|T_JS | int(11) |  | YES  |   | 	 	| 
|T_YCS | int(11) |  | YES  |   | 	 	| 
|JXL | char(3) |  | YES  |   | 	 	| 
|JS | varchar(20) |  | YES  |   | 	 	| 
|JSLX | char(2) |  | YES  |   | 	 	| 
|sxh | char(1) |  | YES  |   | 	 	| 
|dzs | char(1) |  | YES  |   | 	 	| 
|timezc | varchar(50) |  | YES  |   | 	 	| 
|tiemjc | varchar(50) |  | YES  |   | 	 	| 
|memo_hb | varchar(200) |  | YES  |   | 	 	| 
|net_xdrs | int(11) |  | YES  |   | 	 	| 
|net_yxrs | int(11) |  | YES  |   | 	 	| 
|memo | varchar(50) |  | YES  |   | 	 	| 
|zs | decimal(18,1) |  | YES  |   | 	 	| 
|ZSFB | char(10) |  | YES  |   | 	 	| 
|sh_flag | char(10) |  | YES  |   | 	 	| 
|qt_flag | char(10) |  | YES  |   | 	 	| 
|skjc | varchar(105) |  | YES  |   | 	 	| 
|Room_kysb | char(1) |  | YES  |   | 	 	| 
|Room_dmtsb | char(1) |  | YES  |   | 	 	| 
|Room_tysb | char(1) |  | YES  |   | 	 	| 
|Room_hdzy | char(1) |  | YES  |   | 	 	| 
|Room_GoNet | char(1) |  | YES  |   | 	 	| 
|KCLB1 | char(2) |  | YES  |   | 	 	| 
|KCLB2 | char(2) |  | YES  |   | 	 	| 
|Sffzxk | varchar(50) |  | YES  |   | 	 	| 
|sffxzsk | char(10) |  | YES  |   | 	 	| 
|skbjmc | varchar(50) |  | YES  |   | 	 	| 
|syxb | char(2) |  | YES  |   | 	 	| 
|xkkg | char(1) |  | YES  |   | 	 	| 
|SkbjZCJC | varchar(500) |  | YES  |   | 	 	| 
|xm | varchar(50) |  | YES  |   | 	 	| 
|zcanalyse | varchar(255) |  | YES  |   | 	 	| 
|SkbjGroupFlag | varchar(1) |  | YES  |   | 	 	| 
|xkrsxzFlag | char(1) |  | YES  |   | 	 	| 
|xscount | decimal(29,1) |  | YES  |   | 	 	| 
|skbj_level | varchar(14) |  | YES  |   | 	 	| 
|ContentID | char(8) |  | YES  |   | 	 	| 
|RefreshFlag | char(1) |  | YES  |   | 	 	| 
|LimitFlag | char(1) |  | YES  |   | 	 	| 
|insert_time	| datetime |  | YES  |   |   |  	 	 
|modify_time	| datetime |  | YES  |   |   |  	 	 
|ParentSKBJ | varchar(12) |  | YES  |   | 	 	| 
|tk_lock | char(1) |  | YES  |   | 	 	| 
|bnu_sjzF | char(1) |  | YES  |   | 	 	| 
|ndxs | decimal(5,4) |  | YES  |   | 	 	| 
|ktbzrs | int(11) |  | YES  |   | 	 	| 
|zzxs01 | int(11) |  | YES  |   | 	 	| 
|zzxs02 | int(11) |  | YES  |   | 	 	| 
|zzxs03 | int(11) |  | YES  |   | 	 	| 
|zzxs04 | int(11) |  | YES  |   | 	 	| 
|zzxs05 | int(11) |  | YES  |   | 	 	| 
|zzxs06 | int(11) |  | YES  |   | 	 	| 
|zzxs07 | int(11) |  | YES  |   | 	 	| 
|zzxs08 | int(11) |  | YES  |   | 	 	| 
|zzxs09 | int(11) |  | YES  |   | 	 	| 
|zzxs10 | int(11) |  | YES  |   | 	 	| 
|zzxs11 | int(11) |  | YES  |   | 	 	| 
|zzxs12 | int(11) |  | YES  |   | 	 	| 
|zzxs13 | int(11) |  | YES  |   | 	 	| 
|zzxs14 | int(11) |  | YES  |   | 	 	| 
|zzxs15 | int(11) |  | YES  |   | 	 	| 
|zzxs16 | int(11) |  | YES  |   | 	 	| 
|zzxs17 | int(11) |  | YES  |   | 	 	| 
|zzxs18 | int(11) |  | YES  |   | 	 	| 
|zzxs19 | int(11) |  | YES  |   | 	 	| 
|zzxs20 | int(11) |  | YES  |   | 	 	| 
|zzxs21 | int(11) |  | YES  |   | 	 	| 
|zzxs22 | int(11) |  | YES  |   | 	 	| 
|zzxs23 | int(11) |  | YES  |   | 	 	| 
|zzxs24 | int(11) |  | YES  |   | 	 	| 
|zzxs25 | int(11) |  | YES  |   | 	 	| 
|zzxs26 | int(11) |  | YES  |   | 	 	| 
|zzxs27 | int(11) |  | YES  |   | 	 	| 
|zzxs28 | int(11) |  | YES  |   | 	 	| 
|zzxs29 | int(11) |  | YES  |   | 	 	| 
|zzxs30 | int(11) |  | YES  |   | 	 	| 
|TaskJXJDF | varchar(1) |  | YES  |   | 	 	| 
|male_rs | int(11) |  | YES  |   | 	 	| 
|female_rs | int(11) |  | YES  |   | 	 	| 
|ArrXS | int(11) |  | YES  |   | 	 	| 
|ArrZzxs | int(11) |  | YES  |   | 	 	| 
|xzbj_xkrs | int(11) |  | YES  |   | 	 	| 
|jxjdbxs | int(11) |  | YES  |   | 	 	| 
|timezc_old | varchar(50) |  | YES  |   | 	 	| 
|WeekCount | decimal(10,1) |  | YES  |   | 	 	| 
|GroupID | int(11) |  | YES  |   | 	 	| 
|HJ_flag | char(1) |  | YES  |   | 	 	| 
|qx_memo | varchar(50) |  | YES  |   | 	 	| 
|xkpc | varchar(8) |  | YES  |   | 	 	| 
|ks_flag | char(1) |  | YES  |   | 	 	| 
|zy_flag | char(1) |  | YES  |   | 	 	| 
|T_CJJS4 | char(7) |  | YES  |   | 	 	| 
|T_CJJS5 | char(7) |  | YES  |   | 	 	| 
|BackWeekFirst | char(1) |  | YES  |   | 	 	| 
|zczjxs | decimal(5,4) |  | YES  |   | 	 	| 
|BJ_FLAG | char(1) |  | YES  |   | 	 	| 
|pkxq | varchar(2) |  | YES  |   | 	 	| 
|hj_timezc | varchar(50) |  | YES  |   | 	 	| 
|hjzcct_flag | char(1) |  | YES  |   | 	 	| 
|cxmtlimitflag | varchar(1) |  | YES  |   | 	 	| 
|jh_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_kh_appraisestandard
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|dm | int(11) |  | NO  |  	是 | 	 |
|item_dm | char(2) |  | NO  |  	 |  	 |
|mc | varchar(254) |  | YES  |   | 	 	| 
|AppraiseStandard | varchar(5000) |  | YES  |   | 	 	| 
|grade1 | decimal(18,2) |  | YES  |   | 	 	| 
|grade2 | decimal(18,2) |  | YES  |   | 	 	| 
|grade3 | decimal(18,2) |  | YES  |   | 	 	| 
|grade4 | decimal(18,2) |  | YES  |   | 	 	| 
|grade5 | decimal(18,2) |  | YES  |   | 	 	| 
|ts_flag | char(2) |  | YES  |   | 	 	| 
|kclx | char(10) |  | YES  |   | 	 	| 
|grade1_mc | varchar(50) |  | YES  |   | 	 	| 
|grade2_mc | varchar(50) |  | YES  |   | 	 	| 
|grade3_mc | varchar(50) |  | YES  |   | 	 	| 
|grade4_mc | varchar(50) |  | YES  |   | 	 	| 
|grade5_mc | varchar(50) |  | YES  |   | 	 	| 
|xn | char(4) |  | NO  |  	 |  	 |
|xq_id | char(1) |  | NO  |  	 |  	 |
|sys_flag | char(1) |  | NO  |  	 |  	 |
|grade6 | decimal(18,2) |  | YES  |   | 	 	| 
|grade7 | decimal(18,2) |  | YES  |   | 	 	| 
|grade6_mc | varchar(50) |  | YES  |   | 	 	| 
|grade7_mc | varchar(50) |  | YES  |   | 	 	| 
|grade11 | decimal(18,2) |  | YES  |   | 	 	| 
|grade21 | decimal(18,2) |  | YES  |   | 	 	| 
|grade31 | decimal(18,2) |  | YES  |   | 	 	| 
|grade41 | decimal(18,2) |  | YES  |   | 	 	| 
|grade51 | decimal(18,2) |  | YES  |   | 	 	| 
|grade61 | decimal(18,2) |  | YES  |   | 	 	| 
|grade71 | decimal(18,2) |  | YES  |   | 	 	| 
|pjfs_flag | char(2) |  | YES  |   | 	 	| 
|user_dm | varchar(10) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_xj_classinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|NJ | char(4) |  | YES  |   | 	 	| 
|BJDM | char(10) |  | NO  |  	 |  	 |
|BJMC | varchar(50) |  | YES  |   | 	 	| 
|BJJC | varchar(50) |  | YES  |   | 	 	| 
|YX_ID | char(2) |  | YES  |   | 	 	| 
|ZY_ID | char(4) |  | YES  |   | 	 	| 
|XZ | varchar(10) |  | YES  |   | 	 	| 
|XQ | varchar(10) |  | YES  |   | 	 	| 
|GDJXL | varchar(10) |  | YES  |   | 	 	| 
|GDJS | varchar(10) |  | YES  |   | 	 	| 
|BJRS | int(11) |  | YES  |   | 	 	| 
|fdyname | varchar(50) |  | YES  |   | 	 	| 
|fdyphone | varchar(50) |  | YES  |   | 	 	| 
|Room_F | int(11) |  | YES  |   | 	 	| 
|code | varchar(10) |  | YES  |   | 	 	| 
|user_dm | varchar(50) |  | YES  |   | 	 	| 
|pkxq | varchar(2) |  | YES  |   | 	 	| 
|useful | char(1) |  | YES  |   | 	 	| 
|gly | varchar(12) |  | YES  |   | 	 	| 
|zyfx | varchar(6) |  | YES  |   | 	 	| 
|ywmc | varchar(50) |  | YES  |   | 	 	| 
|charge | varchar(10) |  | YES  |   | 	 	| 
|charge_phone | varchar(20) |  | YES  |   | 	 	| 
|fdy2name | varchar(100) |  | YES  |   | 	 	| 
|fdy2phone | varchar(50) |  | YES  |   | 	 	| 
|dsname | varchar(100) |  | YES  |   | 	 	| 
|dsphone | varchar(50) |  | YES  |   | 	 	| 
|ds2name | varchar(100) |  | YES  |   | 	 	| 
|ds2phone | varchar(50) |  | YES  |   | 	 	| 
|bzrname | varchar(100) |  | YES  |   | 	 	| 
|bzrphone | varchar(50) |  | YES  |   | 	 	| 
|bzr2name | varchar(100) |  | YES  |   | 	 	| 
|bzr2phone | varchar(50) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_xj_classinfo_temp
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|BJDM | char(10) |  | YES  |   | 	 	| 
|BJMC | varchar(50) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_xj_nationinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | char(2) |  | NO  |  	 |  	 |
|MC | varchar(30) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_xj_reginfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XN | char(4) |  | NO  |  	 |  	 |
|XQ | char(4) |  | NO  |  	 |  	 |
|XH | char(12) |  | NO  |  	 |  	 |
|ssbj_id | varchar(10) |  | YES  |   | 	 	| 
|sfzx | char(1) |  | YES  |   | 	 	| 
|xjzt | char(2) |  | YES  |   | 	 	| 
|RQ	| datetime |  | YES  |   |   |  	 	 
|ZK | char(2) |  | YES  |   | 	 	| 
|BZ | varchar(200) |  | YES  |   | 	 	| 
|forcezc | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_xj_studbaseinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|RXNJ | char(4) |  | YES  |   | 	 	| 
|XH | char(12) |  | NO  |  	 |  	 |
|SSBJ_ID | varchar(10) |  | YES  |   | 	 	| 
|XSZH | varchar(12) |  | YES  |   | 	 	| 
|XJBH | char(7) |  | YES  |   | 	 	| 
|XJLB_ID | char(2) |  | YES  |   | 	 	| 
|XJLB_ID1 | char(2) |  | YES  |   | 	 	| 
|GKZKZH | varchar(50) |  | YES  |   | 	 	| 
|XM | varchar(50) |  | YES  |   | 	 	| 
|CYM | varchar(50) |  | YES  |   | 	 	| 
|XMPY | varchar(50) |  | YES  |   | 	 	| 
|XB | char(1) |  | YES  |   | 	 	| 
|SFZH | varchar(18) |  | YES  |   | 	 	| 
|CSRQ	| datetime |  | YES  |   |   |  	 	 
|MZDM_ID | char(2) |  | YES  |   | 	 	| 
|JG_ID | varchar(50) |  | YES  |   | 	 	| 
|SYSF_ID | varchar(6) |  | YES  |   | 	 	| 
|SYDW | varchar(200) |  | YES  |   | 	 	| 
|DQDM | varchar(20) |  | YES  |   | 	 	| 
|LXDZ | varchar(500) |  | YES  |   | 	 	| 
|SJR | varchar(50) |  | YES  |   | 	 	| 
|ZP	longblob	 	  | YES  |  	 	 
|ZZMM_ID | char(2) |  | YES  |   | 	 	| 
|RDTSJ	| datetime |  | YES  |   |   |  	 	 
|YZBM | char(6) |  | YES  |   | 	 	| 
|LXDH | varchar(50) |  | YES  |   | 	 	| 
|WHCD_ID | char(2) |  | YES  |   | 	 	| 
|RXPZH | varchar(20) |  | YES  |   | 	 	| 
|RXCHJ	float	 	  | YES  |  	 	 
|RXSJ	| datetime |  | YES  |   |   |  	 	 
|RXFS_ID | char(2) |  | YES  |   | 	 	| 
|LY_ID | char(4) |  | YES  |   | 	 	| 
|LB_ID | char(2) |  | YES  |   | 	 	| 
|BYLBDM | char(2) |  | YES  |   | 	 	| 
|WHFS | char(6) |  | YES  |   | 	 	| 
|TGJC | char(6) |  | YES  |   | 	 	| 
|DAHH | char(4) |  | YES  |   | 	 	| 
|DAYH | char(10) |  | YES  |   | 	 	| 
|XZNJ | char(4) |  | YES  |   | 	 	| 
|HJLB | char(8) |  | YES  |   | 	 	| 
|BZ | varchar(1000) |  | YES  |   | 	 	| 
|KLDML | varchar(10) |  | YES  |   | 	 	| 
|WYYZDM | varchar(20) |  | YES  |   | 	 	| 
|TC | char(2) |  | YES  |   | 	 	| 
|passwd | varchar(50) |  | YES  |   | 	 	| 
|SFYD | char(1) |  | YES  |   | 	 	| 
|SFZX | char(1) |  | YES  |   | 	 	| 
|PYLB_ID | char(2) |  | YES  |   | 	 	| 
|p_Flag | char(1) |  | YES  |   | 	 	| 
|p_Flag_FB | char(1) |  | YES  |   | 	 	| 
|HHBYTJ | varchar(1) |  | YES  |   | 	 	| 
|xjzt | char(2) |  | YES  |   | 	 	| 
|CSD | varchar(200) |  | YES  |   | 	 	| 
|JSZH | char(10) |  | YES  |   | 	 	| 
|YLZH | char(10) |  | YES  |   | 	 	| 
|SSH | varchar(50) |  | YES  |   | 	 	| 
|LSZRF | varchar(50) |  | YES  |   | 	 	| 
|HKZRF | varchar(50) |  | YES  |   | 	 	| 
|MCPXBJ | char(1) |  | YES  |   | 	 	| 
|SHBJ | char(6) |  | YES  |   | 	 	| 
|YSHBJ | char(6) |  | YES  |   | 	 	| 
|TYDB | char(6) |  | YES  |   | 	 	| 
|DXYWKS | char(8) |  | YES  |   | 	 	| 
|SG | char(5) |  | YES  |   | 	 	| 
|TZ | char(5) |  | YES  |   | 	 	| 
|XXDM | char(5) |  | YES  |   | 	 	| 
|XXXS_ID | char(2) |  | YES  |   | 	 	| 
|KSTZ_ID | char(2) |  | YES  |   | 	 	| 
|SFDEXSXW | char(2) |  | YES  |   | 	 	| 
|SFZDS | varchar(4) |  | YES  |   | 	 	| 
|SFSFS | char(2) |  | YES  |   | 	 	| 
|GATDM_ID | char(2) |  | YES  |   | 	 	| 
|JKZK_ID | char(2) |  | YES  |   | 	 	| 
|FY | char(24) |  | YES  |   | 	 	| 
|fxnj | char(4) |  | YES  |   | 	 	| 
|FXZY | char(30) |  | YES  |   | 	 	| 
|FXZYFX | char(24) |  | YES  |   | 	 	| 
|ZYFX | char(24) |  | YES  |   | 	 	| 
|SFLDM | char(8) |  | YES  |   | 	 	| 
|XXNX | char(3) |  | YES  |   | 	 	| 
|XSZYZH | char(5) |  | YES  |   | 	 	| 
|ZXWYJBMC | char(1) |  | YES  |   | 	 	| 
|JSJDJ | char(1) |  | YES  |   | 	 	| 
|NJ | char(2) |  | YES  |   | 	 	| 
|BYB | char(2) |  | YES  |   | 	 	| 
|THBJ | char(6) |  | YES  |   | 	 	| 
|BXLX | char(1) |  | YES  |   | 	 	| 
|LQZY | varchar(200) |  | YES  |   | 	 	| 
|photopath | varchar(100) |  | YES  |   | 	 	| 
|ss_phone | varchar(20) |  | YES  |   | 	 	| 
|p_flag_new | char(1) |  | YES  |   | 	 	| 
|studtype | varchar(50) |  | YES  |   | 	 	| 
|lqtime	| datetime |  | YES  |   |   |  	 	 
|bdtime	| datetime |  | YES  |   |   |  	 	 
|jftime	| datetime |  | YES  |   |   |  	 	 
|zctime	| datetime |  | YES  |   |   |  	 	 
|vxh | varchar(50) |  | YES  |   | 	 	| 
|vzy | varchar(30) |  | YES  |   | 	 	| 
|pylb_true | varchar(50) |  | YES  |   | 	 	| 
|pydx | varchar(50) |  | YES  |   | 	 	| 
|xhqd | varchar(50) |  | YES  |   | 	 	| 
|email | varchar(50) |  | YES  |   | 	 	| 
|xhcode | int(11) |  | YES  |   | 	 	| 
|inserttype | int(11) |  | YES  |   | 	 	| 
|insertuser | varchar(50) |  | YES  |   | 	 	| 
|inserttime	| datetime |  | YES  |   |   |  	 	 
|modifyuser | varchar(50) |  | YES  |   | 	 	| 
|modifytime	| datetime |  | YES  |   |   |  	 	 
|ggrxkc_yx | int(11) |  | YES  |   | 	 	| 
|TYKC_YX | int(11) |  | YES  |   | 	 	| 
|XXKC_YX | int(11) |  | YES  |   | 	 	| 
|zyrxkc_yx | int(11) |  | YES  |   | 	 	| 
|lxcause | longtext |	 	  | YES  | |   |  	 	 
|xjh | char(17) |  | YES  |   | 	 	| 
|end_flag | char(1) |  | YES  |   | 	 	| 
|SS_DM | varchar(50) |  | YES  |   | 	 	| 
|CH_DM | varchar(50) |  | YES  |   | 	 	| 
|force | char(1) |  | YES  |   | 	 	| 
|user_xh | varchar(50) |  | YES  |   | 	 	| 
|kstz | varchar(255) |  | YES  |   | 	 	| 
|lxrdh | varchar(11) |  | YES  |   | 	 	| 
|yzz | varchar(100) |  | YES  |   | 	 	| 
|ypcs | varchar(100) |  | YES  |   | 	 	| 
|bankcard | varchar(50) |  | YES  |   | 	 	| 
|tccj | decimal(18,2) |  | YES  |   | 	 	| 
|zszg | varchar(12) |  | YES  |   | 	 	| 
|yjxf | decimal(18,2) |  | YES  |   | 	 	| 
|graduatestud_flag | char(1) |  | YES  |   | 	 	| 
|sfzs_flag | char(1) |  | YES  |   | 	 	| 
|sfdk_flag | char(1) |  | YES  |   | 	 	| 
|sfbx_flag | char(1) |  | YES  |   | 	 	| 
|Assessor | char(7) |  | YES  |   | 	 	| 
|Recorder | char(7) |  | YES  |   | 	 	| 
| | No  |  tice_Print | no  |   | varchar(50) |  | YES  |   | 	 	| 
|LQPC | varchar(2) |  | YES  |   | 	 	| 
|TDZY | char(1) |  | YES  |   | 	 	| 
|Ecard | varchar(18) |  | YES  |   | 	 	| 
|xz | char(3) |  | YES  |   | 	 	| 
|marriage | char(2) |  | YES  |   | 	 	| 
|xmpyj | varchar(50) |  | YES  |   | 	 	| 
|ltx_flag | varchar(50) |  | YES  |   | 	 	| 
|yzw | varchar(100) |  | YES  |   | 	 	| 
|yzwjb | varchar(100) |  | YES  |   | 	 	| 
|ltx | char(1) |  | YES  |   | 	 	| 
|zwjb | char(4) |  | YES  |   | 	 	| 
|zwdm | char(4) |  | YES  |   | 	 	| 
|zjxy | char(2) |  | YES  |   | 	 	| 
|dszn | char(1) |  | YES  |   | 	 	| 
|zykcj | decimal(4,1) |  | YES  |   | 	 	| 
|mobilephone | varchar(25) |  | YES  |   | 	 	| 
|shbx_code | varchar(30) |  | YES  |   | 	 	| 
|zhic | varchar(3) |  | YES  |   | 	 	| 
|gzdw | varchar(100) |  | YES  |   | 	 	| 
|gzsj	| datetime |  | YES  |   |   |  	 	 
|Print_Flag | char(1) |  | YES  |   | 	 	| 
|sbpc | varchar(50) |  | YES  |   | 	 	| 
|getxjrq	| datetime |  | YES  |   |   |  	 	 
|temp_passwd | varchar(50) |  | YES  |   | 	 	| 
|daoshi | varchar(7) |  | YES  |   | 	 	| 
|eng_xh | varchar(20) |  | YES  |   | 	 	| 
|gkksh | varchar(50) |  | YES  |   | 	 	| 
|dqxxnx | varchar(10) |  | YES  |   | 	 	| 
|txdz | varchar(200) |  | YES  |   | 	 	| 
|modify_flag | varchar(1) |  | YES  |   | 	 	| 
|tyzx | varchar(6) |  | YES  |   | 	 	| 
|end_station | varchar(200) |  | YES  |   | 	 	| 
|khyh | varchar(100) |  | YES  |   | 	 	| 
|TSXSLB | char(2) |  | YES  |   | 	 	| 
|glzt | char(1) |  | YES  |   | 	 	| 
|eng_xh1 | varchar(20) |  | YES  |   | 	 	| 
|eng_xh2 | varchar(20) |  | YES  |   | 	 	| 
|eng_xh3 | varchar(20) |  | YES  |   | 	 	| 
|first_name | varchar(20) |  | YES  |   | 	 	| 
|end_name | varchar(20) |  | YES  |   | 	 	| 
|XSLB | varchar(6) |  | YES  |   | 	 	| 
|dace | varchar(50) |  | YES  |   | 	 	| 
|ccyhk | varchar(20) |  | YES  |   | 	 	| 
|FindPwdQuestion | varchar(500) |  | YES  |   | 	 	| 
|FindPwdAnswer | varchar(500) |  | YES  |   | 	 	| 
|WLKL | char(1) |  | YES  |   | 	 	| 
|DiningCard | varchar(50) |  | YES  |   | 	 	| 
|zszg1 | varchar(7) |  | YES  |   | 	 	| 
|bmh | varchar(10) |  | YES  |   | 	 	| 
|jz_phone | varchar(20) |  | YES  |   | 	 	| 
|zsr | varchar(20) |  | YES  |   | 	 	| 
|zsbm | varchar(100) |  | YES  |   | 	 	| 
|endstation | varchar(50) |  | YES  |   | 	 	| 
|dazt | char(1) |  | YES  |   | 	 	| 
|qq | varchar(20) |  | YES  |   | 	 	| 
|PZDW | varchar(100) |  | YES  |   | 	 	| 
|bdrq | varchar(50) |  | YES  |   | 	 	| 
|ddsj	| datetime |  | YES  |   |   |  	 	 
|ybd_flag | char(1) |  | YES  |   | 	 	| 
|hjszd | varchar(20) |  | YES  |   | 	 	| 
|sfdszn | varchar(2) |  | YES  |   | 	 	| 
|sfdq | varchar(2) |  | YES  |   | 	 	| 
|xgflag | varchar(1) |  | YES  |   | 	 	| 
|byzy | varchar(100) |  | YES  |   | 	 	| 
|dygxrdflag | char(1) |  | YES  |   | 	 	| 
|ems | varchar(20) |  | YES  |   | 	 	| 
|gkcjx01 | decimal(8,2) |  | YES  |   | 	 	| 
|gkcjx02 | decimal(8,2) |  | YES  |   | 	 	| 
|gkcjx03 | decimal(8,2) |  | YES  |   | 	 	| 
|gkcjx04 | decimal(8,2) |  | YES  |   | 	 	| 
|gkcjx05 | decimal(8,2) |  | YES  |   | 	 	| 
|jfje | decimal(12,2) |  | YES  |   | 	 	| 
|yylb | varchar(8) |  | YES  |   | 	 	| 
| | no  |  te_prtflag | char(1) |  | YES  |   | 	 	| 
|bjzw | varchar(50) |  | YES  |   | 	 	| 
|fb_Flag | char(1) |  | YES  |   | 	 	| 
|hkszd | varchar(6) |  | YES  |   | 	 	| 
|jtnzsr | int(11) |  | YES  |   | 	 	| 
|jtrjsr | int(11) |  | YES  |   | 	 	| 
|sfdb | varchar(1) |  | YES  |   | 	 	| 
|srly | varchar(255) |  | YES  |   | 	 	| 
|SFKN | char(1) |  | YES  |   | 	 	| 
|SSMZ | char(1) |  | YES  |   | 	 	| 
|lqxs | char(1) |  | YES  |   | 	 	| 
|lxrq	| datetime |  | YES  |   |   |  	 	 
|sflx | varchar(1) |  | YES  |   | 	 	| 
|rylx | varchar(2) |  | YES  |   | 	 	| 
|zypm | int(11) |  | YES  |   | 	 	| 
|bjpm | int(11) |  | YES  |   | 	 	| 
|xwwyxf | decimal(8,2) |  | YES  |   | 	 	| 
|byyxxf | decimal(8,2) |  | YES  |   | 	 	| 
|gkcjx06 | decimal(8,2) |  | YES  |   | 	 	| 
|gkcjx07 | decimal(8,2) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_xj_studbaseinfo_del
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|RXNJ | char(4) |  | YES  |   | 	 	| 
|XH | char(12) |  | YES  |   | 	 	| 
|SSBJ_ID | varchar(10) |  | YES  |   | 	 	| 
|XSZH | char(11) |  | YES  |   | 	 	| 
|XJBH | char(7) |  | YES  |   | 	 	| 
|XJLB_ID | char(2) |  | YES  |   | 	 	| 
|XJLB_ID1 | char(2) |  | YES  |   | 	 	| 
|GKKSH | char(15) |  | YES  |   | 	 	| 
|GKZKZH | varchar(50) |  | YES  |   | 	 	| 
|XM | varchar(50) |  | YES  |   | 	 	| 
|CYM | varchar(50) |  | YES  |   | 	 	| 
|XMPY | varchar(50) |  | YES  |   | 	 	| 
|XB | char(1) |  | YES  |   | 	 	| 
|SFZH | varchar(18) |  | YES  |   | 	 	| 
|CSRQ	| datetime |  | YES  |   |   |  	 	 
|MZDM_ID | char(2) |  | YES  |   | 	 	| 
|JG_ID | varchar(50) |  | YES  |   | 	 	| 
|SYSF_ID | varchar(6) |  | YES  |   | 	 	| 
|SYDW | varchar(40) |  | YES  |   | 	 	| 
|DQDM | varchar(20) |  | YES  |   | 	 	| 
|LXDZ | varchar(60) |  | YES  |   | 	 	| 
|SJR | varchar(50) |  | YES  |   | 	 	| 
|ZP	longblob	 	  | YES  |  	 	 
|ZZMM_ID | char(2) |  | YES  |   | 	 	| 
|RDTSJ	| datetime |  | YES  |   |   |  	 	 
|YZBM | char(6) |  | YES  |   | 	 	| 
|LXDH | varchar(50) |  | YES  |   | 	 	| 
|WHCD_ID | char(2) |  | YES  |   | 	 	| 
|RXPZH | varchar(20) |  | YES  |   | 	 	| 
|RXCHJ	float	 	  | YES  |  	 	 
|RXSJ	| datetime |  | YES  |   |   |  	 	 
|RXFS_ID | char(2) |  | YES  |   | 	 	| 
|LY_ID | char(4) |  | YES  |   | 	 	| 
|LB_ID | char(2) |  | YES  |   | 	 	| 
|BYLBDM | char(2) |  | YES  |   | 	 	| 
|WHFS | char(6) |  | YES  |   | 	 	| 
|TGJC | char(6) |  | YES  |   | 	 	| 
|DAHH | char(4) |  | YES  |   | 	 	| 
|DAYH | char(10) |  | YES  |   | 	 	| 
|XZNJ | char(4) |  | YES  |   | 	 	| 
|HJLB | char(8) |  | YES  |   | 	 	| 
|BZ | varchar(50) |  | YES  |   | 	 	| 
|KLDML | varchar(10) |  | YES  |   | 	 	| 
|WYYZDM | varchar(20) |  | YES  |   | 	 	| 
|TC | char(2) |  | YES  |   | 	 	| 
|passwd | varchar(50) |  | YES  |   | 	 	| 
|SFYD | char(1) |  | YES  |   | 	 	| 
|SFZX | char(1) |  | YES  |   | 	 	| 
|PYLB_ID | char(2) |  | YES  |   | 	 	| 
|p_Flag | char(1) |  | YES  |   | 	 	| 
|p_Flag_FB | char(1) |  | YES  |   | 	 	| 
|HHBYTJ | varchar(1) |  | YES  |   | 	 	| 
|xjzt | char(2) |  | YES  |   | 	 	| 
|CSD | char(20) |  | YES  |   | 	 	| 
|JSZH | char(10) |  | YES  |   | 	 	| 
|YLZH | char(10) |  | YES  |   | 	 	| 
|SSH | varchar(50) |  | YES  |   | 	 	| 
|LSZRF | varchar(50) |  | YES  |   | 	 	| 
|HKZRF | varchar(50) |  | YES  |   | 	 	| 
|MCPXBJ | char(1) |  | YES  |   | 	 	| 
|SHBJ | char(6) |  | YES  |   | 	 	| 
|YSHBJ | char(6) |  | YES  |   | 	 	| 
|TYDB | char(6) |  | YES  |   | 	 	| 
|DXYWKS | char(8) |  | YES  |   | 	 	| 
|SG | char(5) |  | YES  |   | 	 	| 
|TZ | char(5) |  | YES  |   | 	 	| 
|XXDM | char(5) |  | YES  |   | 	 	| 
|XXXS_ID | char(2) |  | YES  |   | 	 	| 
|KSTZ_ID | char(2) |  | YES  |   | 	 	| 
|SFDEXSXW | char(2) |  | YES  |   | 	 	| 
|SFZDS | char(2) |  | YES  |   | 	 	| 
|SFSFS | char(2) |  | YES  |   | 	 	| 
|GATDM_ID | char(2) |  | YES  |   | 	 	| 
|JKZK_ID | char(2) |  | YES  |   | 	 	| 
|FY | char(24) |  | YES  |   | 	 	| 
|fxnj | char(4) |  | YES  |   | 	 	| 
|FXZY | char(30) |  | YES  |   | 	 	| 
|FXZYFX | char(24) |  | YES  |   | 	 	| 
|ZYFX | char(24) |  | YES  |   | 	 	| 
|SFLDM | char(8) |  | YES  |   | 	 	| 
|XXNX | char(3) |  | YES  |   | 	 	| 
|XSZYZH | char(5) |  | YES  |   | 	 	| 
|ZXWYJBMC | char(1) |  | YES  |   | 	 	| 
|JSJDJ | char(1) |  | YES  |   | 	 	| 
|NJ | char(2) |  | YES  |   | 	 	| 
|BYB | char(2) |  | YES  |   | 	 	| 
|THBJ | char(6) |  | YES  |   | 	 	| 
|BXLX | char(1) |  | YES  |   | 	 	| 
|LQZY | varchar(200) |  | YES  |   | 	 	| 
|photopath | varchar(100) |  | YES  |   | 	 	| 
|ss_phone | varchar(20) |  | YES  |   | 	 	| 
|p_flag_new | char(1) |  | YES  |   | 	 	| 
|studtype | varchar(2) |  | YES  |   | 	 	| 
|lqtime	| datetime |  | YES  |   |   |  	 	 
|bdtime	| datetime |  | YES  |   |   |  	 	 
|jftime	| datetime |  | YES  |   |   |  	 	 
|zctime	| datetime |  | YES  |   |   |  	 	 
|vxh | varchar(50) |  | YES  |   | 	 	| 
|vzy | varchar(30) |  | YES  |   | 	 	| 
|pylb_true | varchar(50) |  | YES  |   | 	 	| 
|pydx | varchar(50) |  | YES  |   | 	 	| 
|xhqd | varchar(50) |  | YES  |   | 	 	| 
|email | varchar(50) |  | YES  |   | 	 	| 
|xhcode | int(11) |  | YES  |   | 	 	| 
|inserttype | int(11) |  | YES  |   | 	 	| 
|insertuser | varchar(50) |  | YES  |   | 	 	| 
|inserttime	| datetime |  | YES  |   |   |  	 	 
|modifyuser | varchar(50) |  | YES  |   | 	 	| 
|modifytime	| datetime |  | YES  |   |   |  	 	 
|ggrxkc_yx | int(11) |  | YES  |   | 	 	| 
|TYKC_YX | int(11) |  | YES  |   | 	 	| 
|XXKC_YX | int(11) |  | YES  |   | 	 	| 
|zyrxkc_yx | int(11) |  | YES  |   | 	 	| 
|lxcause | longtext |	 	  | YES  | |   |  	 	 
|xjh | char(17) |  | YES  |   | 	 	| 
|end_flag | char(1) |  | YES  |   | 	 	| 
|SS_DM | varchar(50) |  | YES  |   | 	 	| 
|CH_DM | varchar(50) |  | YES  |   | 	 	| 
|force | char(1) |  | YES  |   | 	 	| 
|user_xh | varchar(50) |  | YES  |   | 	 	| 
|kstz | varchar(255) |  | YES  |   | 	 	| 
|bankcard | varchar(50) |  | YES  |   | 	 	| 
|lxrdh | varchar(11) |  | YES  |   | 	 	| 
|tccj | decimal(18,2) |  | YES  |   | 	 	| 
|yzz | varchar(100) |  | YES  |   | 	 	| 
|ypcs | varchar(100) |  | YES  |   | 	 	| 
|zszg | char(7) |  | YES  |   | 	 	| 
|yjxf | decimal(18,2) |  | YES  |   | 	 	| 
|Ecard | varchar(18) |  | YES  |   | 	 	| 
|Assessor | char(7) |  | YES  |   | 	 	| 
|Recorder | char(7) |  | YES  |   | 	 	| 
|LQPC | varchar(2) |  | YES  |   | 	 	| 
|graduatestud_flag | char(1) |  | YES  |   | 	 	| 
|sfzs_flag | char(1) |  | YES  |   | 	 	| 
|sfdk_flag | char(1) |  | YES  |   | 	 	| 
|sfbx_flag | char(1) |  | YES  |   | 	 	| 
| | No  |  tice_Print | no  |   | char(6) |  | YES  |   | 	 	| 
|TDZY | char(1) |  | YES  |   | 	 	| 
|id | bigint(20) |  | NO  |  是	 | 	 |
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_building
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(4) |  | NO  |  	 |  	 |
|MC | varchar(50) |  | YES  |   | 	 	| 
|layer | int(11) |  | YES  |   | 	 	| 
|SSDW | varchar(50) |  | YES  |   | 	 	| 
|SZWZ | varchar(50) |  | YES  |   | 	 	| 
|KYJS | int(11) |  | YES  |   | 	 	| 
|user_dm | char(10) |  | YES  |   | 	 	| 
|lx_id | varchar(10) |  | YES  |   | 	 	| 
|status | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_classroominfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(14) |  | NO  |  	 |  	 |
|MC | varchar(254) |  | YES  |   | 	 	| 
|LX_ID | varchar(2) |  | YES  |   | 	 	| 
|RL | int(11) |  | YES  |   | 	 	| 
|SSDW_ID | varchar(7) |  | YES  |   | 	 	| 
|sysid | char(5) |  | YES  |   | 	 	| 
|Layer | int(11) |  | YES  |   | 	 	| 
|SZWZ | varchar(50) |  | YES  |   | 	 	| 
|ZT | varchar(1) |  | YES  |   | 	 	| 
|MPH | varchar(40) |  | YES  |   | 	 	| 
|TYPE_FLAG | char(2) |  | YES  |   | 	 	| 
|school_area | char(2) |  | YES  |   | 	 	| 
|KC_RL | int(11) |  | YES  |   | 	 	| 
|ZZXS | decimal(18,1) |  | YES  |   | 	 	| 
|CDMJ | decimal(18,2) |  | YES  |   | 	 	| 
|user_dm | char(10) |  | YES  |   | 	 	| 
|Room_kysb | char(1) |  | YES  |   | 	 	| 
|Room_dmtsb | char(1) |  | YES  |   | 	 	| 
|Room_tysb | char(1) |  | YES  |   | 	 	| 
|Room_hdzy | char(1) |  | YES  |   | 	 	| 
|Room_GoNet | char(1) |  | YES  |   | 	 	| 
|arear | decimal(18,2) |  | YES  |   | 	 	| 
|room_f | int(11) |  | YES  |   | 	 	| 
|symj | decimal(18,2) |  | YES  |   | 	 	| 
|fzr | varchar(50) |  | YES  |   | 	 	| 
|memo | longtext |	 	  | YES  | |   |  	 	 
|OpenFlag | char(1) |  | YES  |   | 	 	| 
|labClass | varchar(2) |  | YES  |   | 	 	| 
|labType | varchar(2) |  | YES  |   | 	 	| 
|buildyear | char(4) |  | YES  |   | 	 	| 
|ZS_KCRL | int(11) |  | YES  |   | 	 	| 
|zylx | char(1) |  | YES  |   | 	 	| 
|ywkt | char(1) |  | YES  |   | 	 	| 
|zyxs | char(1) |  | YES  |   | 	 	| 
|dmlx | char(1) |  | YES  |   | 	 	| 
|zwfbz | int(11) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_degreeinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(2) |  | NO  |  	 |  	 |
|MC | varchar(32) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_departmentinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(5) |  | YES  |   | 	 	| 
|ZWMC | varchar(60) |  | YES  |   | 	 	| 
|ZWJC | varchar(32) |  | YES  |   | 	 	| 
|YWMC | varchar(50) |  | YES  |   | 	 	| 
|YWJC | varchar(50) |  | YES  |   | 	 	| 
|ZGBM | varchar(24) |  | YES  |   | 	 	| 
|YZ | varchar(8) |  | YES  |   | 	 	| 
|SJ | varchar(8) |  | YES  |   | 	 	| 
|LXR | varchar(8) |  | YES  |   | 	 	| 
|DH | varchar(20) |  | YES  |   | 	 	| 
|CZ | varchar(14) |  | YES  |   | 	 	| 
|DZYJ | varchar(50) |  | YES  |   | 	 	| 
|DZ | varchar(50) |  | YES  |   | 	 	| 
|YB | char(6) |  | YES  |   | 	 	| 
|passwd | char(11) |  | YES  |   | 	 	| 
|ment_flag | char(1) |  | YES  |   | 	 	| 
|user_dm | char(10) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_diplomainfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(2) |  | NO  |  	 |  	 |
|MC | varchar(32) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_duty
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|dm | varchar(4) |  | NO  |  	 |  	 |
|mc | varchar(50) |  | YES  |   | 	 	| 
|sys_flag | char(10) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_instituteinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(5) |  | NO  |  	 |  	 |
|ZWMC | varchar(32) |  | YES  |   | 	 	| 
|ZWJC | varchar(32) |  | YES  |   | 	 	| 
|YWMC | varchar(150) |  | YES  |   | 	 	| 
|YWJC | varchar(50) |  | YES  |   | 	 	| 
|ZGBM | varchar(24) |  | YES  |   | 	 	| 
|YZ | varchar(8) |  | YES  |   | 	 	| 
|SJ | varchar(8) |  | YES  |   | 	 	| 
|LXR | varchar(8) |  | YES  |   | 	 	| 
|DH | varchar(50) |  | YES  |   | 	 	| 
|CZ | varchar(14) |  | YES  |   | 	 	| 
|DZYJ | varchar(50) |  | YES  |   | 	 	| 
|DZ | varchar(50) |  | YES  |   | 	 	| 
|YB | varchar(6) |  | YES  |   | 	 	| 
|School_Area | varchar(10) |  | YES  |   | 	 	| 
|ment_flag | char(1) |  | YES  |   | 	 	| 
|user_dm | char(10) |  | YES  |   | 	 	| 
|dhjc | varchar(20) |  | YES  |   | 	 	| 
|ssdw_id | varchar(5) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_professioninfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(3) |  | NO  |  	 |  	 |
|MC | varchar(32) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
|p_flag | char(1) |  | YES  |   | 	 	| 
|SYS_DM | char(3) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_school_area
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(10) |  | NO  |  	 |  	 |
|MC | varchar(50) |  | YES  |   | 	 	| 
|BZ | varchar(100) |  | YES  |   | 	 	| 
|JC | varchar(50) |  | YES  |   | 	 	| 
|dz | varchar(50) |  | YES  |   | 	 	| 
|yzbm | char(8) |  | YES  |   | 	 	| 
|user_dm | varchar(10) |  | YES  |   | 	 	| 
|station | varchar(4) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_schoolinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(6) |  | NO  |  	 |  	 |
|ZWMC | varchar(32) |  | YES  |   | 	 	| 
|ZWJC | varchar(32) |  | YES  |   | 	 	| 
|YWMC | varchar(100) |  | YES  |   | 	 	| 
|YWJC | varchar(50) |  | YES  |   | 	 	| 
|XXXZ_ID | varchar(10) |  | YES  |   | 	 	| 
|XXLB_ID | varchar(10) |  | YES  |   | 	 	| 
|ZGBM | varchar(24) |  | YES  |   | 	 	| 
|XZ | varchar(50) |  | YES  |   | 	 	| 
|SJ | varchar(50) |  | YES  |   | 	 	| 
|LXR | varchar(50) |  | YES  |   | 	 	| 
|DH | varchar(20) |  | YES  |   | 	 	| 
|CZ | varchar(14) |  | YES  |   | 	 	| 
|DZYJ | varchar(50) |  | YES  |   | 	 	| 
|WZ | varchar(50) |  | YES  |   | 	 	| 
|DZ | varchar(50) |  | YES  |   | 	 	| 
|YB | char(6) |  | YES  |   | 	 	| 
|Jxgl_flag | char(1) |  | YES  |   | 	 	| 
|PZWH | varchar(50) |  | YES  |   | 	 	| 
|user_dm | varchar(10) |  | YES  |   | 	 	| 
|railwaystation | varchar(50) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_specialityinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(4) |  | NO  |  	 |  	 |
|GBZYDM | varchar(8) |  | YES  |   | 	 	| 
|ZWMC | varchar(50) |  | YES  |   | 	 	| 
|ZWJC | varchar(14) |  | YES  |   | 	 	| 
|YWMC | varchar(254) |  | YES  |   | 	 	| 
|YWJC | varchar(50) |  | YES  |   | 	 	| 
|PYCC | char(6) |  | YES  |   | 	 	| 
|XZ | varchar(3) |  | YES  |   | 	 	| 
|ZGBM | varchar(24) |  | YES  |   | 	 	| 
|XWMC | char(20) |  | YES  |   | 	 	| 
|XK | char(10) |  | YES  |   | 	 	| 
|PYFX | varchar(100) |  | YES  |   | 	 	| 
|kssj | char(4) |  | YES  |   | 	 	| 
|sffx | char(10) |  | YES  |   | 	 	| 
|pydx | char(2) |  | YES  |   | 	 	| 
|user_dm | char(10) |  | YES  |   | 	 	| 
|syxw | char(2) |  | YES  |   | 	 	| 
|bnu_zgbm | varchar(2) |  | YES  |   | 	 	| 
|fx_flag | char(1) |  | YES  |   | 	 	| 
|memo | longtext |	 	  | YES  | |   |  	 	 
|Tag | varchar(60) |  | YES  |   | 	 	| 
|State | char(1) |  | YES  |   | 	 	| 
|sfldm | char(1) |  | YES  |   | 	 	| 
|xs | int(11) |  | YES  |   | 	 	| 
|bxlb | char(2) |  | YES  |   | 	 	| 
|pxlx1 | char(2) |  | YES  |   | 	 	| 
|pxlx2 | char(2) |  | YES  |   | 	 	| 
|bxxs | varchar(2) |  | YES  |   | 	 	| 
|XKML | varchar(6) |  | YES  |   | 	 	| 
|YJXK | varchar(6) |  | YES  |   | 	 	| 
|EJXK | varchar(6) |  | YES  |   | 	 	| 
|SYXWLX | char(1) |  | YES  |   | 	 	| 
|flag_zydl | char(1) |  | YES  |   | 	 	| 
|zydl | varchar(4) |  | YES  |   | 	 	| 
|achieve_inst | varchar(50) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_staffroominfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | char(5) |  | NO  |  	 |  	 |
|ZWMC | varchar(60) |  | YES  |   | 	 	| 
|ZWJC | varchar(32) |  | YES  |   | 	 	| 
|YWMC | varchar(50) |  | YES  |   | 	 	| 
|YWJC | varchar(50) |  | YES  |   | 	 	| 
|ZGBM | varchar(24) |  | YES  |   | 	 	| 
|YZ | varchar(8) |  | YES  |   | 	 	| 
|SJ | varchar(8) |  | YES  |   | 	 	| 
|LXR | varchar(8) |  | YES  |   | 	 	| 
|DH | varchar(50) |  | YES  |   | 	 	| 
|CZ | varchar(14) |  | YES  |   | 	 	| 
|DZYJ | varchar(50) |  | YES  |   | 	 	| 
|DZ | varchar(50) |  | YES  |   | 	 	| 
|YB | varchar(6) |  | YES  |   | 	 	| 
|user_dm | char(10) |  | YES  |   | 	 	| 
|ment_flag | char(1) |  | YES  |   | 	 	| 
|type_flag | char(2) |  | YES  |   | 	 	| 
|fzr | varchar(7) |  | YES  |   | 	 	| 
|cdmj | decimal(18,2) |  | YES  |   | 	 	| 
|arear | decimal(18,2) |  | YES  |   | 	 	| 
|symj | decimal(18,2) |  | YES  |   | 	 	| 
|dhjc | varchar(20) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_teacherinfo
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(7) |  | NO  |  	 |  	 |
|XM | varchar(50) |  | YES  |   | 	 	| 
|XB | varchar(2) |  | YES  |   | 	 	| 
|CSRQ | varchar(14) |  | YES  |   | 	 	| 
|XL_ID | varchar(10) |  | YES  |   | 	 	| 
|XW_ID | varchar(10) |  | YES  |   | 	 	| 
|ZC_ID | varchar(20) |  | YES  |   | 	 	| 
|TSSF_ID | varchar(2) |  | YES  |   | 	 	| 
|SSDW_ID | varchar(50) |  | YES  |   | 	 	| 
|SRKC | varchar(100) |  | YES  |   | 	 	| 
|SZGW | varchar(50) |  | YES  |   | 	 	| 
|SFZG | varchar(1) |  | YES  |   | 	 	| 
|yjfx | varchar(254) |  | YES  |   | 	 	| 
|sjyjl | varchar(512) |  | YES  |   | 	 	| 
|gzjl | varchar(512) |  | YES  |   | 	 	| 
|shxsjz | varchar(254) |  | YES  |   | 	 	| 
|kycg | varchar(254) |  | YES  |   | 	 	| 
|hjry | varchar(254) |  | YES  |   | 	 	| 
|address | varchar(254) |  | YES  |   | 	 	| 
|email | varchar(50) |  | YES  |   | 	 	| 
|rxrq | varchar(20) |  | YES  |   | 	 	| 
|jys | char(100) |  | YES  |   | 	 	| 
|mz | char(20) |  | YES  |   | 	 	| 
|jg | varchar(50) |  | YES  |   | 	 	| 
|zzmm | varchar(50) |  | YES  |   | 	 	| 
|byyx | varchar(100) |  | YES  |   | 	 	| 
|bysj | varchar(50) |  | YES  |   | 	 	| 
|sxzy | varchar(100) |  | YES  |   | 	 	| 
|gzsj	| datetime |  | YES  |   |   |  	 	 
|jszc | char(2) |  | YES  |   | 	 	| 
|jssj | varchar(50) |  | YES  |   | 	 	| 
|xzzw | varchar(50) |  | YES  |   | 	 	| 
|zcxl | char(10) |  | YES  |   | 	 	| 
|zcjb | char(10) |  | YES  |   | 	 	| 
|sfzh | varchar(18) |  | YES  |   | 	 	| 
|gl | int(11) |  | YES  |   | 	 	| 
|nld | char(20) |  | YES  |   | 	 	| 
|gh | varchar(50) |  | YES  |   | 	 	| 
|grjl | longtext |	 	  | YES  | |   |  	 	 
|passwd | varchar(50) |  | YES  |   | 	 	| 
|e_mail | char(100) |  | YES  |   | 	 	| 
|zp	longblob	 	  | YES  |  	 	 
|csrq_2	| datetime |  | YES  |   |   |  	 	 
|wj | varchar(50) |  | YES  |   | 	 	| 
|photopath | varchar(100) |  | YES  |   | 	 	| 
|xmpyall | varchar(100) |  | YES  |   | 	 	| 
|xmpy1 | varchar(20) |  | YES  |   | 	 	| 
|zjjs_flag | char(1) |  | YES  |   | 	 	| 
|jszgz_flag | char(1) |  | YES  |   | 	 	| 
|sjhm | char(11) |  | YES  |   | 	 	| 
|temp_passwd | varchar(50) |  | YES  |   | 	 	| 
|ssjxbm | varchar(50) |  | YES  |   | 	 	| 
|prbmkj | char(1) |  | YES  |   | 	 	| 
|rzsj	| datetime |  | YES  |   |   |  	 	 
|FindPwdQuestion | varchar(500) |  | YES  |   | 	 	| 
|FindPwdAnswer | varchar(500) |  | YES  |   | 	 	| 
|xgry | char(1) |  | YES  |   | 	 	| 
|zc_hqsj	| datetime |  | YES  |   |   |  	 	 
|zczgzs | varchar(50) |  | YES  |   | 	 	| 
|zczgzs_hqsj	| datetime |  | YES  |   |   |  	 	 
|dhjc | varchar(20) |  | YES  |   | 	 	| 
|fdy_flag | char(1) |  | YES  |   | 	 	| 
|zw | varchar(10) |  | YES  |   | 	 	| 
|gwlx | varchar(10) |  | YES  |   | 	 	| 
|qdxlsj	| datetime |  | YES  |   |   |  	 	 
|qdxwsj	| datetime |  | YES  |   |   |  	 	 
|gw_rzsj	| datetime |  | YES  |   |   |  	 	 
|sjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|grad_school | varchar(32) |  | YES  |   | 	 	| 
|first_xl | varchar(6) |  | YES  |   | 	 	| 
|xz | varchar(6) |  | YES  |   | 	 	| 
|zy | varchar(254) |  | YES  |   | 	 	| 
|gradu_yx | varchar(254) |  | YES  |   | 	 	| 
|gradu_sj | varchar(10) |  | YES  |   | 	 	| 
|xgflag | varchar(1) |  | YES  |   | 	 	| 
|fdy_gznx | int(11) |  | YES  |   | 	 	| 
|sxxwzy | varchar(100) |  | YES  |   | 	 	| 
|xwlx | varchar(20) |  | YES  |   | 	 	| 
|xwgrad_school | varchar(32) |  | YES  |   | 	 	| 
|ky_xm | varchar(100) |  | YES  |   | 	 	| 
|ky_fblw | varchar(100) |  | YES  |   | 	 	| 
|ky_cbzz | varchar(100) |  | YES  |   | 	 	| 
|ky_hj | varchar(100) |  | YES  |   | 	 	| 
|px_gwfxcs | varchar(10) |  | YES  |   | 	 	| 
|px_gnfxcs | varchar(10) |  | YES  |   | 	 	| 
|px_xjcs | varchar(10) |  | YES  |   | 	 	| 
|px_gzdlcs | varchar(10) |  | YES  |   | 	 	| 
|gjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|tjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|dsjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|xjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|jb | varchar(100) |  | YES  |   | 	 	| 
|jz_flag | char(1) |  | YES  |   | 	 	| 
|zyzgzs | varchar(100) |  | YES  |   | 	 	| 
|byxx1 | varchar(500) |  | YES  |   | 	 	| 
|sxzy1 | varchar(500) |  | YES  |   | 	 	| 
|byxx2 | varchar(500) |  | YES  |   | 	 	| 
|sxzy2 | varchar(500) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## t_zy_teacherinfo_copy_copy
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | varchar(7) |  | NO  |  	 |  	 |
|XM | varchar(50) |  | YES  |   | 	 	| 
|XB | varchar(2) |  | YES  |   | 	 	| 
|CSRQ | varchar(14) |  | YES  |   | 	 	| 
|XL_ID | varchar(10) |  | YES  |   | 	 	| 
|XW_ID | varchar(10) |  | YES  |   | 	 	| 
|ZC_ID | varchar(20) |  | YES  |   | 	 	| 
|TSSF_ID | varchar(2) |  | YES  |   | 	 	| 
|SSDW_ID | varchar(50) |  | YES  |   | 	 	| 
|SRKC | varchar(100) |  | YES  |   | 	 	| 
|SZGW | varchar(50) |  | YES  |   | 	 	| 
|SFZG | varchar(1) |  | YES  |   | 	 	| 
|yjfx | varchar(254) |  | YES  |   | 	 	| 
|sjyjl | varchar(512) |  | YES  |   | 	 	| 
|gzjl | varchar(512) |  | YES  |   | 	 	| 
|shxsjz | varchar(254) |  | YES  |   | 	 	| 
|kycg | varchar(254) |  | YES  |   | 	 	| 
|hjry | varchar(254) |  | YES  |   | 	 	| 
|address | varchar(254) |  | YES  |   | 	 	| 
|email | varchar(50) |  | YES  |   | 	 	| 
|rxrq | varchar(20) |  | YES  |   | 	 	| 
|jys | char(100) |  | YES  |   | 	 	| 
|mz | char(20) |  | YES  |   | 	 	| 
|jg | varchar(50) |  | YES  |   | 	 	| 
|zzmm | varchar(50) |  | YES  |   | 	 	| 
|byyx | varchar(100) |  | YES  |   | 	 	| 
|bysj | varchar(50) |  | YES  |   | 	 	| 
|sxzy | varchar(100) |  | YES  |   | 	 	| 
|gzsj	| datetime |  | YES  |   |   |  	 	 
|jszc | char(2) |  | YES  |   | 	 	| 
|jssj | varchar(50) |  | YES  |   | 	 	| 
|xzzw | varchar(50) |  | YES  |   | 	 	| 
|zcxl | char(10) |  | YES  |   | 	 	| 
|zcjb | char(10) |  | YES  |   | 	 	| 
|sfzh | varchar(18) |  | YES  |   | 	 	| 
|gl | int(11) |  | YES  |   | 	 	| 
|nld | char(20) |  | YES  |   | 	 	| 
|gh | varchar(50) |  | YES  |   | 	 	| 
|grjl | longtext |	 	  | YES  | |   |  	 	 
|passwd | varchar(50) |  | YES  |   | 	 	| 
|e_mail | char(100) |  | YES  |   | 	 	| 
|zp	longblob	 	  | YES  |  	 	 
|csrq_2	| datetime |  | YES  |   |   |  	 	 
|wj | varchar(50) |  | YES  |   | 	 	| 
|photopath | varchar(100) |  | YES  |   | 	 	| 
|xmpyall | varchar(100) |  | YES  |   | 	 	| 
|xmpy1 | varchar(20) |  | YES  |   | 	 	| 
|zjjs_flag | char(1) |  | YES  |   | 	 	| 
|jszgz_flag | char(1) |  | YES  |   | 	 	| 
|sjhm | char(11) |  | YES  |   | 	 	| 
|temp_passwd | varchar(50) |  | YES  |   | 	 	| 
|ssjxbm | varchar(50) |  | YES  |   | 	 	| 
|prbmkj | char(1) |  | YES  |   | 	 	| 
|rzsj	| datetime |  | YES  |   |   |  	 	 
|FindPwdQuestion | varchar(500) |  | YES  |   | 	 	| 
|FindPwdAnswer | varchar(500) |  | YES  |   | 	 	| 
|xgry | char(1) |  | YES  |   | 	 	| 
|zc_hqsj	| datetime |  | YES  |   |   |  	 	 
|zczgzs | varchar(50) |  | YES  |   | 	 	| 
|zczgzs_hqsj	| datetime |  | YES  |   |   |  	 	 
|dhjc | varchar(20) |  | YES  |   | 	 	| 
|fdy_flag | char(1) |  | YES  |   | 	 	| 
|zw | varchar(10) |  | YES  |   | 	 	| 
|gwlx | varchar(10) |  | YES  |   | 	 	| 
|qdxlsj	| datetime |  | YES  |   |   |  	 	 
|qdxwsj	| datetime |  | YES  |   |   |  	 	 
|gw_rzsj	| datetime |  | YES  |   |   |  	 	 
|sjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|grad_school | varchar(32) |  | YES  |   | 	 	| 
|first_xl | varchar(6) |  | YES  |   | 	 	| 
|xz | varchar(6) |  | YES  |   | 	 	| 
|zy | varchar(254) |  | YES  |   | 	 	| 
|gradu_yx | varchar(254) |  | YES  |   | 	 	| 
|gradu_sj | varchar(10) |  | YES  |   | 	 	| 
|xgflag | varchar(1) |  | YES  |   | 	 	| 
|fdy_gznx | int(11) |  | YES  |   | 	 	| 
|sxxwzy | varchar(100) |  | YES  |   | 	 	| 
|xwlx | varchar(20) |  | YES  |   | 	 	| 
|xwgrad_school | varchar(32) |  | YES  |   | 	 	| 
|ky_xm | varchar(100) |  | YES  |   | 	 	| 
|ky_fblw | varchar(100) |  | YES  |   | 	 	| 
|ky_cbzz | varchar(100) |  | YES  |   | 	 	| 
|ky_hj | varchar(100) |  | YES  |   | 	 	| 
|px_gwfxcs | varchar(10) |  | YES  |   | 	 	| 
|px_gnfxcs | varchar(10) |  | YES  |   | 	 	| 
|px_xjcs | varchar(10) |  | YES  |   | 	 	| 
|px_gzdlcs | varchar(10) |  | YES  |   | 	 	| 
|gjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|tjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|dsjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|xjpx_demo | longtext |	 	  | YES  | |   |  	 	 
|jb | varchar(100) |  | YES  |   | 	 	| 
|jz_flag | char(1) |  | YES  |   | 	 	| 
|zyzgzs | varchar(100) |  | YES  |   | 	 	| 
|byxx1 | varchar(500) |  | YES  |   | 	 	| 
|sxzy1 | varchar(500) |  | YES  |   | 	 	| 
|byxx2 | varchar(500) |  | YES  |   | 	 	| 
|sxzy2 | varchar(500) |  | YES  |   | 	 	| 
|_MASK_TO_V2 | bigint(20) |  | YES  |   | 	 	| 
 

## test
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|uid | int(4) |  | NO  |  是	 | 	 |
|name | varchar(10) |  | NO  |  	 |  	 |
|pwd | varchar(10) |  | YES  |   | 	 	| 


## v_kb_stutable(视图)
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|XH | char(12) |  | NO  |  	 |  	 |
|XM | varchar(50) |  | YES  |   | 	 	| 
|KC_FLAG | char(1) |  | YES  |   | 	 	| 
|XN | char(4) |  | NO  |  	 |  	 |
|XQ_ID | char(1) |  | NO  |  	 |  	 |
|SKBJ | varchar(12) |  | NO  |  	 |  	 |
|NJ | char(4) |  | YES  |   | 	 	| 
|DM | char(6) |  | NO  |  	 |  	 |
|ZWMC | varchar(255) |  | YES  |   | 	 	| 
|JCz | char(10) |  | NO  |  	 |  	 |
|MC | varchar(254) |  | YES  |   | 	 	| 
|DSZ | char(1) |  | NO  |  	 |  	 |
|stimezc | varchar(50) |  | NO  |  	 |  	 |
|jsxm | varchar(50) |  | YES  |   | 	 	| 
|KSZ | int(11) |  | YES  |   | 	 	| 
|JSZ | int(11) |  | YES  |   | 	 	| 
|ZXS | decimal(18,1) |  | YES  |   | 	 	| 
|JCInfo | varchar(50) |  | YES  |   | 	 	| 


## view_xj_hlpxxlxdm(视图)
|字段名 | 数据类型	| 默认值	| 允许非空 | 自动递增 | 备注 |
|------|---------|-------|--------|---------|-----|
|DM | char(1) |  | NO  |  	 |  	 |
|MC | char(30) |  | YES  |   | 	 	| 
|sys_flag | char(1) |  | YES  |   | 	 	| 
