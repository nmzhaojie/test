<template>
	<div>
		<div class="bread-crumb">
			<el-breadcrumb separator=">>">
				 <el-breadcrumb-item><i class="el-icon-setting"></i> 自述</el-breadcrumb-item>
			</el-breadcrumb>
		</div>
		<div class="ms-doc">
            <h3>停车场空位查询系统</h3>
            <article>
                <h1>manage-system</h1>
                <p>基于vue的停车场管理系统</p>
                <h2>前言</h2>
                <p>为了解决用户寻找附近停车场不方便的问题，决定设计一个能够迅速查询附近的停车场的信息的系统，给用户提供更好的建议来选择停车场</p>

                <h2>功能</h2>
              
                <el-checkbox disabled checked>登录/注销</el-checkbox>
                <br>
                <el-checkbox disabled checked>停车场列表显示</el-checkbox>
                <br>
                <el-checkbox disabled checked>定位</el-checkbox>
                <br>
                <el-checkbox disabled checked>导航</el-checkbox>
                <br>
                <el-checkbox disabled checked>搜索</el-checkbox>
                <br>
                <el-checkbox disabled checked>支持切换主题色</el-checkbox>
                <br>
                <el-checkbox disabled checked>更多</el-checkbox>
                <br>
            </article>
        </div>
	</div>
</template>

<style scoped>
	.ms-doc{
        width:100%;
        max-width: 980px;
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    }
    .ms-doc h3{
        padding: 9px 10px 10px;
        margin: 0;
        font-size: 14px;
        line-height: 17px;
        background-color: #f5f5f5;
        border: 1px solid #d8d8d8;
        border-bottom: 0;
        border-radius: 3px 3px 0 0;
    }
    .ms-doc article{
        padding: 45px;
        word-wrap: break-word;
        background-color: #fff;
        border: 1px solid #ddd;
        border-bottom-right-radius: 3px;
        border-bottom-left-radius: 3px;
    }
    .ms-doc article h1{
        font-size:32px;
        padding-bottom: 10px;
        margin-bottom: 15px;
        border-bottom: 1px solid #ddd;
    }
    .ms-doc article h2 {
        margin: 24px 0 16px;
        font-weight: 600;
        line-height: 1.25;
        padding-bottom: 7px;
        font-size: 24px;
        border-bottom: 1px solid #eee;
    }
    .ms-doc article p{
        margin-bottom: 15px;
        line-height: 1.5;
    }
    .ms-doc article .el-checkbox{
        margin-bottom: 5px;
    }
</style>
