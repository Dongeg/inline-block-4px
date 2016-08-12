# inline-block-4px
inline-block 元素之间4像素空隙解决方案

方法一 改变代码结构

如：
        
        <ul>
        <li></li><li></li><li></li><li></li>
        </ul>
        
方法二



        ul{
          font-size:0;
          letter-spacing:-4px; /*实际情况下 -4这个值可能还要调整*/
          word-spacing:-4px;   /*实际情况下 -4这个值可能还要调整*/   
        }
        ul li{
          display:inline-bolck;
          zoom:1;
          font-size:12px;
          letter-spacing:normal;
          word-spacing:normal;
        }
