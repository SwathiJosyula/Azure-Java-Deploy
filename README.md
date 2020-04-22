# Azure-Java-Deploy
Deploying code via eclipse 
package Azure;
import org.openqa.selenium.chrome.ChromeDriver;

public class GoogleSearch {

	public static void main(String[] args) throws Exception {

		//open chrome browser
		System.setProperty("webdriver.chrome.driver", "C:\\Users\\Swathi\\Desktop\\selenium project\\chromedriver_win32\\chromedriver.exe");
		ChromeDriver driver = new ChromeDriver();
				
		//Maximize the screen
		driver.manage().window().maximize();
		
		//open Google Application
		driver.get("http://google.co.in");
