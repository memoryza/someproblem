##1.IE css选择器限制
  A sheet may contain up to 4095 rules

  A sheet may @import up to 31 sheets

  @import nesting supports up to 4 levels deep

出现在ie9及以下。<a href="http://support.microsoft.com/kb/262161" >原文</a>

Update: IE10 Platform Preview #2 significantly raises the limits described above. In IE10 (any browser/document mode):


  A sheet may contain up to 65534 rules

  A document may use up to 4095 stylesheets

  @import nesting is limited to 4095 levels (due to the 4095 stylesheet limit)

<a href="http://blogs.msdn.com/b/ieinternals/archive/2011/05/14/10164546.aspx">更新</a>
