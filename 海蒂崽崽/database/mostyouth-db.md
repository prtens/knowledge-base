# mostyouth数据库数据字典

## building (教学楼表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 教学楼名称 | 
| code | varchar(255) | | NO |   | 教学楼编码 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| dept_id | int(10) unsigned | 0 | NO |   | 所属系别 | 
| floor_count | tinyint(3) unsigned | 0 | NO |   | 楼层数量 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## classroom (教室表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 教室名称 | 
| code | varchar(255) | | NO |   | 教室编码 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| dept_id | int(10) unsigned | 0 | NO |   | 所属系别 | 
| building_id | int(10) unsigned | 0 | NO |   | 所属教学楼 | 
| capacity | int(10) unsigned | 0 | NO |   | 容量 | 
| floor | tinyint(3) unsigned | 0 | NO |   | 所在楼层 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## clazz (班级表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 班级名称 | 
| code | varchar(255) | | NO |   | 班级编码 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| dept_id | int(10) unsigned | 0 | NO |   | 所属系别 | 
| major_id | int(10) unsigned | 0 | NO |   | 所属专业 | 
| grade | varchar(32) | | NO |   | 年级 | 
| teacher | int(10) unsigned | 0 | NO |   | 班主任用户ID | 
| supervisor | int(10) unsigned | 0 | NO |   | 辅导员用户ID | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## clazz_course (班级课表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| clazz_id | int(10) unsigned | | NO |   | 所属班级 | 
| course_id | int(10) unsigned | | NO |   | 所属课程 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 更新时间 | 

## college (学院表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 学院名称 | 
| code | varchar(255) | | NO |   | 学院编码 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| dean | int(10) unsigned | 0 | NO |   | 院长用户ID | 
| secretary | int(10) unsigned | 0 | NO |   | 书记用户ID | 
| major_count | int(10) unsigned | 0 | NO |   | 专业数量 | 
| student_count | int(10) unsigned | 0 | NO |   | 学生数量 | 
| teacher_count | int(10) unsigned | 0 | NO |   | 教师数量 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## course (课程表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 课程名称 | 
| code | varchar(255) | | NO |   | 课程编码 | 
| term_id | int(10) unsigned | 0 | NO |   | 所属学期 | 
| category_id | int(10) unsigned | 0 | NO |   | 所属分类 | 
| course_template_id | int(10) unsigned | 0 | NO |   | 所属的课程模板 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| dept_id | int(10) unsigned | 0 | NO |   | 所属系别 | 
| major_id | int(10) unsigned | 0 | NO |   | 所属专业 | 
| clazz_ids | varchar(255) | | NO |   | 班级ids | 
| classroom_id | int(10) unsigned | 0 | NO |   | 上课教室 | 
| cycle_weeks | varchar(255) | | NO |   | 周期周次:|1|2|3| | 
| cycle_days | varchar(255) | | NO |   | 周期星期:|1|5| | 
| cycle_lessons | varchar(255) | | NO |   | 周期星期:|1|2|3|4| | 
| credit | int(10) unsigned | 0 | NO |   | 学分 | 
| period | int(10) unsigned | 0 | NO |   | 学时 | 
| type | varchar(32) | required | NO |   | 类型(必修,选修) | 
| teacher | int(10) unsigned | 0 | NO |   | 班主任用户ID | 
| student_count | int(10) unsigned | 0 | NO |   | 学生数量 | 
| creator | int(10) unsigned | 0 | NO |   | 创建者ID | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## course_category (课程分类表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 分类名称 | 
| code | varchar(255) | | NO |   | 分类编码 | 
| course_count | int(10) unsigned | 0 | NO |   | 课程数量 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## course_member (选课表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| course_id | int(10) unsigned | | NO |   | 所属课程 | 
| user_id | int(10) unsigned | | NO |   | 所属用户 | 
| role | varchar(32) | | NO |   | 用户类型:teacher,student | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| credit | int(10) unsigned | 0 | NO |   | 已获得的学分 | 
| attended_count | int(10) unsigned | 0 | NO |   | 出勤次数 | 
| not_attended_count | int(10) unsigned | 0 | NO |   | 缺勤次数 | 
| last_attended_time | int(10) unsigned | 0 | NO |   | 最近一次出勤时间 | 
| remark | varchar(512) | | NO |   | 备注 | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 更新时间 | 

## course_template (课程模板表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 课程名称 | 
| code | varchar(255) | | NO |   | 课程编码 | 
| category_id | int(10) unsigned | 0 | NO |   | 所属分类 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| credit | int(10) unsigned | 0 | NO |   | 学分 | 
| period | int(10) unsigned | 0 | NO |   | 学时 | 
| type | varchar(32) | required | NO |   | 类型(必修,选修) | 
| creator | int(10) unsigned | 0 | NO |   | 创建者ID | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 更新时间 | 

## dept (系别表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 系名 | 
| code | varchar(255) | | NO |   | 系别编码 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| dean | int(10) unsigned | 0 | NO |   | 院长用户ID | 
| major_count | int(10) unsigned | 0 | NO |   | 专业数量 | 
| student_count | int(10) unsigned | 0 | NO |   | 学生数量 | 
| teacher_count | int(10) unsigned | 0 | NO |   | 教师数量 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## log (系统日志)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | | 
| user_id | int(10) unsigned | 0 | NO |   | | 
| module | varchar(32) | | NO |   | | 
| action | varchar(32) | | NO |   | | 
| message | text | | NO |   | | 
| data | text | | YES |   | | 
| ip | varchar(255) | | NO |   | | 
| created_time | int(10) unsigned | | NO |   | | 
| level | varchar(10) | | NO |   | | 

## major (专业表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 专业名称 | 
| code | varchar(255) | | NO |   | 专业编码 | 
| gb_code | varchar(255) | | NO |   | 国标编码 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| dept_id | int(10) unsigned | 0 | NO |   | 所属系别 | 
| student_count | int(10) unsigned | 0 | NO |   | 学生数量 | 
| year | varchar(32) | | NO |   | 学制 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## migrations ()

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| version | varchar(255) | | NO |   | | 

## organization (机构表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 机构名称 | 
| code | varchar(255) | | NO |   | 机构编码 | 
| parent_id | int(10) unsigned | 0 | NO |   | 上级机构 | 
| depth | int(10) unsigned | 0 | NO |   | 层级 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| user_count | int(10) unsigned | 0 | NO |   | 人员数量 | 
| leader | int(10) unsigned | 0 | NO |   | 负责人用户ID | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## school (校区表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 校区名称 | 
| code | varchar(255) | | NO |   | 机构编码 | 
| leader | int(10) unsigned | 0 | NO |   | 负责人用户ID | 
| address | varchar(255) | | NO |   | 校区地址 | 
| small_picture | varchar(255) | | NO |   | 小图片 | 
| medium_picture | varchar(255) | | NO |   | 中图片 | 
| large_picture | varchar(255) | | NO |   | 大图片 | 
| dept_count | int(10) unsigned | 0 | NO |   | 系别数量 | 
| college_count | int(10) unsigned | 0 | NO |   | 学院数量 | 
| major_count | int(10) unsigned | 0 | NO |   | 专业数量 | 
| student_count | int(10) unsigned | 0 | NO |   | 学生数量 | 
| teacher_count | int(10) unsigned | 0 | NO |   | 教师数量 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 

## setting ()

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | | 
| name | varchar(255) | | NO |   | | 
| value | longblob | | YES |   | | 

## term (学期表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| name | varchar(255) | | NO |   | 名称 | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| start_time | int(10) unsigned | 0 | NO |   | 开始时间 | 
| end_time | int(10) unsigned | 0 | NO |   | 结束时间 | 
| sort | int(10) unsigned | 0 | NO |   | 排序值(大到小) | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 更新时间 | 

## user (用户表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| nickname | varchar(255) | | NO |   | 昵称 | 
| mobile | varchar(255) | | NO |   | 手机号码 | 
| email | varchar(255) | | NO |   | 邮箱 | 
| type | varchar(32) | | NO |   | 类型:teacher,student | 
| school_id | int(10) unsigned | 0 | NO |   | 所属校区 | 
| organization_id | int(10) unsigned | 0 | NO |   | 所属的主要组织机构ID | 
| college_id | int(10) unsigned | 0 | NO |   | 所属学院 | 
| dept_id | int(10) unsigned | 0 | NO |   | 所属系别 | 
| major_id | int(10) unsigned | 0 | NO |   | 所属专业(教师为0) | 
| clazz_id | int(10) unsigned | 0 | NO |   | 所属班级(教师为0) | 
| number | varchar(64) | | NO |   | 学号/工号 | 
| salt | varchar(32) | | NO |   | 密码SALT | 
| password | varchar(64) | | NO |   | 用户密码 | 
| roles | varchar(255) | | NO |   | 用户角色 | 
| small_avatar | varchar(255) | | NO |   | 小头像 | 
| medium_avatar | varchar(255) | | NO |   | 中头像 | 
| large_avatar | varchar(255) | | NO |   | 大头像 | 
| sex | char(10) | | NO |   | 性别 | 
| locked | tinyint(1) unsigned | 0 | NO |   | 是否被禁止 | 
| new_notification_num | int(10) unsigned | 0 | NO |   | 未读消息数 | 
| created_ip | varchar(64) | | NO |   | 注册IP | 
| created_time | int(10) unsigned | 0 | NO |   | 注册时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 
| login_time | int(11) | 0 | NO |   | 最后登录时间 | 
| login_ip | varchar(64) | | NO |   | 最后登录IP | 

## user_organization (用户组织机构关联表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| user_id | int(10) unsigned | | NO |   | 所属组织机构 | 
| organization_id | int(10) unsigned | | NO |   | 所属用户 | 
| created_time | int(10) unsigned | 0 | NO |   | 创建时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 更新时间 | 

## user_profile (用户配置表)

|字段名|数据类型|默认值|允许非空|自动递增|备注|
|-----|-------|-----|------|-------|----|
| id | int(10) unsigned | | NO | 是 | ID | 
| user_id | int(10) unsigned | 0 | NO |   | 所属用户 | 
| type | varchar(32) | | NO |   | 类型:teacher,student | 
| title | varchar(64) | | NO |   | 头衔/职称 | 
| realname | varchar(64) | | NO |   | 真实姓名 | 
| realname_spell | varchar(128) | | NO |   | 真实姓名拼音 | 
| former_name | varchar(64) | | NO |   | 曾用名 | 
| birthday | int(10) unsigned | 0 | NO |   | 生日 | 
| birthplace | varchar(32) | | NO |   | 籍贯 | 
| nation | varchar(32) | | NO |   | 民族 | 
| politics_status | varchar(64) | | NO |   | 政治面貌 | 
| id_card | varchar(32) | | NO |   | 身份证号码 | 
| phone | varchar(32) | | NO |   | 联系电话 | 
| address | varchar(255) | | NO |   | 联系地址 | 
| about | text | | YES |   | 简介/简历 | 
| contacter_name | varchar(32) | | NO |   | 其他联系人姓名 | 
| contacter_phone | varchar(32) | | NO |   | 其他联系人电话 | 
| contacter_address | varchar(255) | | NO |   | 其他联系人地址 | 
| enrolled_time | int(10) unsigned | 0 | NO |   | 入学/入职时间 | 
| current_degree | varchar(64) | | NO |   | 当前在读学历 | 
| last_degree | varchar(64) | | NO |   | 最高学历 | 
| is_clazz_teacher | tinyint(1) unsigned | 0 | NO |   | 是否担任班主任 | 
| is_clazz_supervisor | tinyint(1) unsigned | 0 | NO |   | 是否担任辅导员 | 
| status | varchar(64) | | NO |   | 在职/在籍状态(normal,leave) | 
| is_repeater | tinyint(1) unsigned | 0 | NO |   | 是否留级 | 
| is_upgraded | tinyint(1) unsigned | 0 | NO |   | 是否专升本 | 
| created_time | int(10) unsigned | 0 | NO |   | 注册时间 | 
| updated_time | int(10) unsigned | 0 | NO |   | 最后更新时间 | 
