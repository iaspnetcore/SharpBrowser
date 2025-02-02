https://www.webdevtutor.net/blog/c-sharp-web-browser-source-code
~~~
using System;
using System.Windows.Forms;

namespace WebBrowserExample
{
    class Program
    {
        static void Main()
        {
            WebBrowser browser = new WebBrowser();
            browser.Navigate("https://www.example.com");
        }
    }
}
~~~
