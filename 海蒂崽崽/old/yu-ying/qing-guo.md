### 青果数据库(表介绍)

#### 一、学生信息类
 * [学生信息表](#T_XJ_StudBaseInfo)
 * [性别](#HLPXB)
 * [学生学年](#T_XJ_RegInfo)
 * [民族](#T_XJ_NationInfo)
 * [地区信息](#hlpdqdm)

#### 二、教师信息类
 * [教师信息](#T_ZY_TeacherInfo)
 * [教研室表](#T_ZY_StaffRoomInfo)
 * [学历表](#T_ZY_DiplomaInfo)
 * [学位表](#T_ZY_DegreeInfo)
 * [教师职位](#T_ZY_ProfessionInfo)
 * [教师岗位表](#T_zy_duty)

#### 三、课程类
 * [课程信息](#T_JH_SetlessonInfo)
 * [课表信息](#T_KB_PLAN)
 * [课程性质表](#T_JH_Lsort1Info)
 * [课表](#T_KB_AUTO_TABLE)
 * [班级课表](#V_KB_LESSON_BJ)
 * [学生课](#V_KB_StuTable)
 * [成绩表](#T_CJ_LessScoreInfo)
 * [每个老师的课表](#T_KB_Task)
 * [教学评量指标](#T_KH_AppraiseStandard)
 * [学期信息](#t_jh_terminfo)
 * [学生选课表](#t_kb_selkc)
 * [成绩表现形式](#T_CJ_Format)
 * [每档成绩划分](#T_CJ_LevelSort)


#### 四、校园信息类
 * [学校表](#T_ZY_Schoolinfo)
 * [校区表](#T_ZY_School_Area)
 * [学院表](#T_ZY_InstituteInfo)
 * [系别表](#T_ZY_DepartmentInfo)
 * [专业信息](#T_ZY_SpecialityInfo)
 * [班级信息表](#T_XJ_ClassInfo)
 * [教室信息](#T_ZY_ClassroomInfo)
 * [教学楼信息](#T_ZY_BUILDING)
 * [学生学籍异动表](#T_XJ_StudChangeInfo)
 * [成绩表](#v_kb_classromm_xsinfo)

<span id="T_XJ_StudBaseInfo">学生信息表 `T_XJ_StudBaseInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>XH</td>
		<td>学号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SSBJ_ID</td>
		<td>班级id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>user_xh</td>
		<td>学号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XM</td>
		<td>姓名</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XMPY</td>
		<td>姓名拼音</td>
		<td>-</td>
	</tr>
	<tr>
		<td>CYM</td>
		<td>曾用名</td>
		<td>-</td>
	</tr>
	<tr>
		<td>GKKSH</td>
		<td>高考考生号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>GKZKZH</td>
		<td>高考准考证号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SFZH</td>
		<td>身份证号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>CSRQ</td>
		<td>出生日期</td>
		<td>-</td>
	</tr>
	<tr>
		<td>JG_ID</td>
		<td>籍贯</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SYDW</td>
		<td>生源单位</td>
		<td>-</td>
	</tr>
	<tr>
		<td>RXCHJ</td>
		<td>入学成绩</td>
		<td>-</td>
	</tr>
	<tr>
		<td>DQDM</td>
		<td>地区代码</td>
		<td>-</td>
	</tr>
	<tr>
		<td>LXDZ</td>
		<td>联系地址</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SJR</td>
		<td>联系人</td>
		<td>-</td>
	</tr>
	<tr>
		<td>LXDH</td>
		<td>联系电话</td>
		<td>-</td>
	</tr>
	<tr>
		<td>YZBM</td>
		<td>邮政编码</td>
		<td>-</td>
	</tr>
	<tr>
		<td>email</td>
		<td>电子邮件</td>
		<td>-</td>
	</tr>
	<tr>
		<td>LQZY</td>
		<td>录取专业</td>
		<td>-</td>
	</tr>
	<tr>
		<td>BZ</td>
		<td>备注</td>
		<td>-</td>
	</tr>
	<tr>
		<td>passwd</td>
		<td>密码</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SFZX</td>
		<td>是否在校</td>
		<td>-</td>
	</tr>
	<tr>
		<td>RXNJ</td>
		<td>入学年份</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XB</td>
		<td>性别</td>
		<td>-</td>
	</tr>
</table>

<span id="HLPXB">性别 `HLPXB`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_XJ_RegInfo">学生学年 `T_XJ_RegInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_XJ_NationInfo">民族 `T_XJ_NationInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="hlpdqdm">地区信息 `hlpdqdm`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_ZY_TeacherInfo">教师信息 `T_ZY_TeacherInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>学号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XM</td>
		<td姓名td>
		<td>-</td>
	</tr>
	<tr>
		<td>XB</td>
		<td>性别</td>
		<td>-</td>
	</tr>
	<tr>
		<td>csrq_2</td>
		<td>出生日期</td>
		<td>-</td>
	</tr>
	<tr>
		<td>sfzh</td>
		<td>身份证号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>passwd</td>
		<td>密码</td>
		<td>-</td>
	</tr>
	<tr>
		<td>Syj</td>
		<td>专业号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZC_ID</td>
		<td>职称id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>rxrq</td>
		<td>入校年份</td>
		<td>-</td>
	</tr>
	<tr>
		<td>gh</td>
		<td>工号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>zwmc</td>
		<td>部门</td>
		<td>-</td>
	</tr>
	<tr>
		<td>jszc</td>
		<td>是否外聘</td>
		<td>-</td>
	</tr>
	<tr>
		<td>gzjl</td>
		<td>备注</td>
		<td>-</td>
	</tr>
	<tr>
		<td>grjl</td>
		<td>简历</td>
		<td>-</td>
	</tr>
	<tr>
		<td>sfzg</td>
		<td>是否在岗</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SSDW_ID</td>
		<td>学院id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>bysj</td>
		<td>联系电话</td>
		<td>-</td>
	</tr>
	<tr>
		<td>email</td>
		<td>电子邮箱</td>
		<td>-</td>
	</tr>
	<tr>
		<td>xmpyall</td>
		<td>姓名拼音</td>
		<td>-</td>
	</tr>
	<tr>
		<td>xmpy1</td>
		<td>姓名拼音简写</td>
		<td>-</td>
	</tr>
	<tr>
		<td>address</td>
		<td>地址</td>
		<td>-</td>
	</tr>
</table>

<span id="T_ZY_StaffRoomInfo">教研室表 `T_ZY_StaffRoomInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_ZY_DiplomaInfo">学历表 `T_ZY_DiplomaInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_ZY_DegreeInfo">学位表 `T_ZY_DegreeInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_ZY_ProfessionInfo">教师职位 `T_ZY_ProfessionInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_zy_duty">教师岗位表 `T_zy_duty`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_JH_SetlessonInfo">课程信息 `T_JH_SetlessonInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>课程编号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZWMC</td>
		<td>课程名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZXF</td>
		<td>学分</td>
		<td>-</td>
	</tr>
	<tr>
		<td>CDDW_ID</td>
		<td>开课院系</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZXS</td>
		<td>period</td>
		<td>-</td>
	</tr>
</table>

<span id="T_XJ_StudChangeInfo">学生学籍异动表 `T_XJ_StudChangeInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_KB_PLAN">课表信息 `T_KB_PLAN`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>XH</td>
		<td>主键</td>
		<td>-</td>
	</tr>
	<tr>
		<td>T_ZJJS</td>
		<td>教师id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>KCID</td>
		<td>课程id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>CDDW_ID</td>
		<td>系id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XN</td>
		<td>学年</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XQ_ID</td>
		<td>学期</td>
		<td>-</td>
	</tr>
	<tr>
		<td>T_SKBJ</td>
		<td>授课信息</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SkbjZCJC</td>
		<td>课程信息</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZXS</td>
		<td>学时</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XF</td>
		<td>学分</td>
		<td>-</td>
	</tr>
</table>


<span id="T_JH_Lsort1Info">课程性质表 `T_JH_Lsort1Info`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>编号、Id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>MC</td>
		<td>名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>Sys_flag</td>
		<td>系统标识</td>
		<td>-</td>
	</tr>
</table>

<span id="T_KB_AUTO_TABLE">课表 `T_KB_AUTO_TABLE`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>XN</td>
		<td>学年</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XQ_ID</td>
		<td>学期</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SKBJ</td>
		<td>设课班级</td>
		<td>-</td>
	</tr>
	<tr>
		<td>DSZ</td>
		<td>单双周</td>
		<td>-</td>
	</tr>
	<tr>
		<td>stimezc</td>
		<td>课程开始结束节数</td>
		<td>-</td>
	</tr>
	<tr>
		<td>JSM</td>
		<td>教室代码</td>
		<td>-</td>
	</tr>
	<tr>
		<td>t_js</td>
		<td>每天节数</td>
		<td>-</td>
	</tr>
	<tr>
		<td>JCAnalyse</td>
		<td></td>
		<td>-</td>
	</tr>
	<tr>
		<td>Analyse</td>
		<td></td>
		<td>-</td>
	</tr>
	<tr>
		<td>KCID</td>
		<td>课程id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>BJDM</td>
		<td>班级</td>
		<td>-</td>
	</tr>
	<tr>
		<td>JCz</td>
		<td>周几</td>
		<td>-</td>
	</tr>
</table>

<span id="v_kb_classromm_xsinfo">成绩表 `v_kb_classromm_xsinfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_CJ_Format">成绩表现形式 `T_CJ_Format`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_CJ_LevelSort">每档成绩划分 `T_CJ_LevelSort`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="t_jh_terminfo">学期信息 `t_jh_terminfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>编号、Id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>MC</td>
		<td>名称</td>
		<td>-</td>
	</tr>
</table>

<span id="t_kb_selkc">学生选课表 `t_kb_selkc`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_ZY_Schoolinfo">学校表 `T_ZY_Schoolinfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>编号、Id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZWMC</td>
		<td>名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XZ</td>
		<td>校长</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SJ</td>
		<td>书记</td>
		<td>-</td>
	</tr>
</table>

<span id="T_ZY_School_Area">校区表 `T_ZY_School_Area`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_ZY_InstituteInfo">学院表 `T_ZY_InstituteInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>编号、Id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZWMC</td>
		<td>名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SJ</td>
		<td>书记</td>
		<td>-</td>
	</tr>
	<tr>
		<td>YZ</td>
		<td>院长</td>
		<td>-</td>
	</tr>
</table>

<span id="T_ZY_DepartmentInfo">系别表 `T_ZY_DepartmentInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>编号、Id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZWMC</td>
		<td>系名</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZGBM</td>
		<td>学院id</td>
		<td>-</td>
	</tr>
</table>

<span id="T_ZY_SpecialityInfo">专业信息 `T_ZY_SpecialityInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>user_dm</td>
		<td>专业代码</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZWMC</td>
		<td>专业名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>GBZYDM</td>
		<td>国标专业代码</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XZ</td>
		<td>学制</td>
		<td>-</td>
	</tr>
	<tr>
		<td>DM</td>
		<td>编号/id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZGBM</td>
		<td>院系id</td>
		<td>-</td>
	</tr>
</table>

<span id="T_XJ_ClassInfo">班级信息表 `T_XJ_ClassInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>NJ</td>
		<td>年级</td>
		<td>-</td>
	</tr>
	<tr>
		<td>BJDM</td>
		<td>班级代码/id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>BJMC</td>
		<td>班级名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>fdyname</td>
		<td>辅导员名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>fdyphone</td>
		<td>辅导员电话</td>
		<td>-</td>
	</tr>
	<tr>
		<td>ZY_ID</td>
		<td>专业id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XY_ID</td>
		<td>院系id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>XZ</td>
		<td>学制</td>
		<td>-</td>
	</tr>
	<tr>
		<td>BJRS</td>
		<td>班级人数</td>
		<td>-</td>
	</tr>
</table>

<span id="T_ZY_ClassroomInfo">教室信息 `T_ZY_ClassroomInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>MC</td>
		<td>名称/id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>RL</td>
		<td>人数</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SZWZ</td>
		<td>教学楼编号</td>
		<td>-</td>
	</tr>
</table>

<span id="T_ZY_BUILDING">教学楼信息 `T_ZY_BUILDING`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>id</td>
		<td>-</td>
	</tr>
	<tr>
		<td>MC</td>
		<td>名称</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SZWZ</td>
		<td>校区编号</td>
		<td>-</td>
	</tr>
	<tr>
		<td>KYSJ</td>
		<td>教室数</td>
		<td>-</td>
	</tr>
</table>

<span id="T_KH_AppraiseStandard">教学评量指标 `T_KH_AppraiseStandard`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="V_KB_LESSON_BJ">班级课表 `V_KB_LESSON_BJ`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="V_KB_StuTable">学生课 `V_KB_StuTable`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_CJ_LessScoreInfo">成绩表 `T_CJ_LessScoreInfo`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>

<span id="T_KB_Task">每个老师的课表 `T_KB_Task`</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>ID</th>
		<th>字段名称</th>
		<th>备注</th>
	</tr>
</table>