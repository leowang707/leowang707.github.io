
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>您的網站標題</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css">
    <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  </head>
  <body>
    <!-- 導覽列 -->
    <nav class="navbar navbar-default">
      <div class="container-fluid" style="background:#428bca"><!-- 可更改背景顏色 -->
        <!-- 導覽列的頁首 -->
        <div class="navbar-header">          
          <a class="navbar-brand" href="#" style="color:white">您的網站名稱</a>
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar">
            <span class="sr-only">導覽按鈕</span>
            <span class="icon-bar" style="background:white"></span>
            <span class="icon-bar" style="background:white"></span>
            <span class="icon-bar" style="background:white"></span>
          </button>
        </div>		
        <!-- 導覽列的項目 -->
        <div id="navbar" class="navbar-collapse collapse">
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">首頁</a></li>
            <li><a href="#您的網頁1" style="color:white">您的頁籤1</a></li>
            <li><a href="#您的網頁2" style="color:white">您的頁籤2</a></li>
            <li><a href="#您的網頁3" style="color:white">您的頁籤3</a></li>
          </ul>			  
          <form class="navbar-form navbar-right" action="http://www.google.com/search" method="get" target="_blank">
            <div class="form-group has-feedback">
              <input type="search" class="form-control" placeholder="請輸入">
              <span class="glyphicon glyphicon-search form-control-feedback"></span>
            </div>
            <button type="submit" class="btn btn-default">搜尋</button>
          </form>
        </div>
      </div>
    </nav>

    <!-- 頁首 -->
    <header>
      <div class="container">
        <h1>您的網站名稱</h1>
        <p class="lead">您的網站簡介</p>
      </div>
    </header>    
	
    <!-- 內容區 -->
    <hr>  
    <div class="container">	  
      <div class="row">
        <!-- 文章 -->
        <article>
          <div class="col-sm-8">
            <h3>您的文章段落1標題</h3>
            <!-- 您的文章段落1內容 -->
            <hr>			
            <h3>您的文章段落2標題</h3>
            <!-- 您的文章段落2內容 -->
            <hr>
            <h3>您的文章段落3標題</h3>
            <!-- 您的文章段落3內容 -->
            <hr>
            <nav>
              <ul class="list-inline text-center">
                <li><a class="btn btn-info btn-lg" href="#您的上一篇網頁">上一篇</a></li>
                <li><a class="btn btn-info btn-lg" href="#您的下一篇網頁">下一篇</a></li>
              </ul>
            </nav>
          </div>
        </article>

        <!-- 側邊欄 --> 		
        <aside>
          <div class="col-sm-3 col-sm-offset-1">
            <!-- 短文側邊框範例 -->
            <div class="panel panel-danger">
              <div class="panel-heading">
                <h3>您的短文側邊框標題</h3>
              </div>
              <div class="panel-body">
                <p>您的短文側邊框內容</p>
              </div>
            </div>
		  
            <!-- 連結清單側邊框範例-->
            <div class="panel panel-warning">
              <div class="panel-heading">
                <h3>您的連結清單側邊框標題</h3>
              </div>
              <div class="panel-body">
                <ol class="list-unstyled">
                  <li><a href="#您的連結網頁1">您的連結名稱1</a></li>
                  <li><a href="#您的連結網頁2">您的連結名稱2</a></li>
                  <li><a href="#您的連結網頁3">您的連結名稱3</a></li>
                  <li><a href="#您的連結網頁4">您的連結名稱4</a></li>
                </ol>
              </div>
            </div>
          </div>
        </aside>		
      </div>
    </div>    
	
    <!-- 頁尾 -->
    <hr> 	
    <footer>  
      <div class="container">
        <p>&copy; 2022 您的網站名稱&middot;<a href="#">隱私權政策</a>&middot;<a href="#">服務條款</a></p>
        <p class="text-right"><a href="#">Back to top</a></p>
      </div>	
    </footer>
  </body>	
</html>
