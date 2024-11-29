# Spotify-X-Path-
Spotify/X-Path 
package com.fb;
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
import java.util.Scanner;
public class SpotifyXPath {

	
	public static void main(String[] args) throws InterruptedException
	{
		WebDriver cr7=new ChromeDriver();
		cr7.get("https://accounts.spotify.com/en/login/");
		cr7.findElement(By.xpath("//input[@autocomplete='username']")).sendKeys("akibmahmud870@gmail.com");
		cr7.findElement(By.xpath("//input[@type='password']")).sendKeys("mosharof9090");
		cr7.findElement(By.xpath("//span[@class='ButtonInner-sc-14ud5tc-0 hvvTXU encore-bright-accent-set']"));
		cr7.findElement(By.xpath("//p[@class='sc-czgmHJ kraIJY']")).click();
		
		cr7.close();
		
	}

}
