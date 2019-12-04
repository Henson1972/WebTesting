import static com.kms.katalon.core.checkpoint.CheckpointFactory.findCheckpoint
import static com.kms.katalon.core.testcase.TestCaseFactory.findTestCase
import static com.kms.katalon.core.testdata.TestDataFactory.findTestData
import static com.kms.katalon.core.testobject.ObjectRepository.findTestObject
import static com.kms.katalon.core.testobject.ObjectRepository.findWindowsObject
import com.kms.katalon.core.checkpoint.Checkpoint as Checkpoint
import com.kms.katalon.core.cucumber.keyword.CucumberBuiltinKeywords as CucumberKW
import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as Mobile
import com.kms.katalon.core.model.FailureHandling as FailureHandling
import com.kms.katalon.core.testcase.TestCase as TestCase
import com.kms.katalon.core.testdata.TestData as TestData
import com.kms.katalon.core.testobject.TestObject as TestObject
import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WS
import com.kms.katalon.core.webui.keyword.WebUiBuiltInKeywords as WebUI
import com.kms.katalon.core.windows.keyword.WindowsBuiltinKeywords as Windows
import internal.GlobalVariable as GlobalVariable
import org.openqa.selenium.Keys as Keys

WebUI.openBrowser('')

WebUI.navigateToUrl('http://automationpractice.com/index.php')

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_My Store/a_Sign in'))

WebUI.setText(findTestObject('Object Repository/Automation Testing/Page_Login - My Store/input_Email address_email'), 'henson_chin@yahoo.com')

WebUI.setEncryptedText(findTestObject('Object Repository/Automation Testing/Page_Login - My Store/input_Password_passwd'), 
    'Ymy980GF6nW2HP5z9znA5w==')

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_Login - My Store/span_Sign in'))

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_My account - My Store/a_Women'))

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_Women - My Store/img_Tops_replace-2x'))

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_Dresses - My Store/img_Browse our different dresses to choose _f853f6'))

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_Summer Dresses - My Store/span_Add to cart'))

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_Summer Dresses - My Store/span_Proceed to checkout'))

WebUI.click(findTestObject('Object Repository/Automation Testing/Page_Order - My Store/a_Sign out'))

