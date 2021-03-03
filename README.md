# SmokeTest
using System; using Xunit; using OpenQA.Selenium; using OpenQA.Selenium.Chrome;  namespace CreditCards.UITests1 {     public class CreditCardWebAppShould     {         [Fact]         [Trait("Category", "Smoke")]         public void LoadApplicationPage1()         {             using (IWebDriver driver = new ChromeDriver())             {             }         }     } }
