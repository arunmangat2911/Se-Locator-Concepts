# Se-Locator-Concepts

package SeleniumSession;

	import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
	import org.openqa.selenium.chrome.ChromeDriver;
	
	
	public class locatorConcept {

		public static void main(String[] args) {
			
				
			System.setProperty("webdriver.chrome.driver", "C:\\Users\\Arun\\eclipse-workspace\\Selenium\\lib\\chromedrivers\\chromedriver.exe");
			WebDriver driver = new  ChromeDriver();
			
			driver.get("https://reg.ebay.com/reg/PartialReg?siteid=0&co_partnerId=0&UsingSSL=1&rv4=1&ru=https%3A%2F%2Fwww.ebay.com%2Fb%2FBreville%2Fbn_21821267%3F_trkparms%3Dpageci%253A61d04948-f7ed-11e8-8afd-74dbd1802a2f%257Cparentrq%253A7a59a82c1670ad7998f5f4bdfff8a3be%257Ciid%253A0&signInUrl=https%3A%2F%2Fwww.ebay.com%2Fsignin%3Fsgn%3Dreg%26siteid%3D0%26co_partnerId%3D0%26UsingSSL%3D1%26rv4%3D1%26ru%3Dhttps%253A%252F%252Fwww.ebay.com%252Fb%252FBreville%252Fbn_21821267%253F_trkparms%253Dpageci%25253A61d04948-f7ed-11e8-8afd-74dbd1802a2f%25257Cparentrq%25253A7a59a82c1670ad7998f5f4bdfff8a3be%25257Ciid%25253A0");
			
			//driver.findElement(By.xpath("//*[@id=\"firstname\"]")).sendKeys("Tom");
			//driver.findElement(By.xpath("//*[@id=\"lastname\"]")).sendKeys("Joseph");
			
		    //driver.findElement(By.id("firstname")).sendKeys("Toommm");
			
				
		    driver.findElement(By.name("lastname")).sendKeys("hilfiger");
		    
		    driver.findElement(By.cssSelector("#firstname")).sendKeys("Tommy");
		    
		    //driver.findElement(By.xpath("//*[@id=\"ppaNav\"]")).click();
		    
		    //driver.findElement(By.linkText("Create a business account")).click();
		    
		    driver.findElement(By.cssSelector("#PASSWORD")).sendKeys("hiasdas");
		    
		    		
		    		
		    
		    
		}
		
	}
