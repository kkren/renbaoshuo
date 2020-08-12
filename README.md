<h3 align="center">👋 Hello! I'm Ren Baoshuo.</h3>

<p align="center">
<a href="https://baoshuo.blog">Blog</a>&nbsp;•&nbsp;
<a href="https://twitter.com/renbaoshuo">Twitter</a>&nbsp;•&nbsp;
<a href="https://github.com/renbaoshuo">GitHub</a>&nbsp;•&nbsp;
<a href="https://gitee.com/renbaoshuo">Gitee</a>&nbsp;•&nbsp;
<a href="https://t.me/baoshuo">Telegram</a>
</p>

<p id="baoshuo-age" align="center" style="display: none;"></p>

<script>
/**
 * 
 * @param {int} year  
 * @param {int} month 
 * @param {int} date 
 * @link  https://github.com/renbaoshuo/baoyun-site
 */
function getAgeInfo(year, month, date) {
  var nowtime = new Date();
  var nyear = nowtime.getUTCFullYear();
  var nmonth = nowtime.getUTCMonth() + 1;
  var nday = nowtime.getUTCDate();
  var r = "";
  if (nmonth == month) {
    if (nday == date) {
      r = `I'm&nbsp;<b>${nyear - year}</b>&nbsp;years&nbsp;old&nbsp;now.<br><b style="color: #dc143c;"><small>Today is my birthday!</small></b>`;
    } else if (nday > date) {
      r = `I'm&nbsp;<b>${nyear - year}</b>&nbsp;years&nbsp;old&nbsp;now.`;
    } else if (nday < date) {
      r = `I'm&nbsp;<b>${nyear - year - 1}</b>&nbsp;years&nbsp;old&nbsp;now.`;
    }
  } else if (nmonth > month) {
    r = `I'm&nbsp;<b>${nyear - year}</b>&nbsp;years&nbsp;old&nbsp;now.`;
  } else if (nmonth < month) {
    r = `I'm&nbsp;<b>${nyear - year - 1}</b>&nbsp;years&nbsp;old&nbsp;now.`;
  }
  return r;
}

document.getElementById('baoshuo-age').innerHTML = getAgeInfo(2006, 06, 04);
document.getElementById('baoshuo-age').style.display = 'block';

</script>

### Github Stats

<a href="https://github.com/renbaoshuo"><img src="https://github-readme-stats.vercel.app/api?username=renbaoshuo&show_icons=true&layout=compact&count_private=true&hide_title=true&theme=default" style="width: 58%; max-width: 58%; min-width: 58%;"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=renbaoshuo&layout=compact&count_private=true&theme=default" style="width: 40%; max-width: 40%; min-width: 40%;"></a>

### Blog Posts

Only the latest **5** articles are displayed here.

<!--START_SECTION:posts-->
- [【多图】在 VMware 上安装 macOS 11 Big Sur Beta](https://baoshuo.blog/post/FYt7XcPaa/)
- [Sakura Frp 使用常见问题](https://baoshuo.blog/post/8tYaUDF47/)
- [修改 Git 配置加速 clone GitHub 源码](https://baoshuo.blog/post/5vwyjylHh/)
- [【补档】handsome 魔改教程：左侧边栏输出优化](https://baoshuo.blog/post/Tqp-Gj-LY/)
- [自定义 git.io 短链接地址与绕过链接生成限制](https://baoshuo.blog/post/oKnaKLcDb/)
<!--END_SECTION:posts-->

**See more on [baoshuo.blog](https://baoshuo.blog).**
