# rakanst 

<html> <head> <title> reCAPTCHA demo: عرض صريح بعد رد اتصال onload </title> <script type = "text / javascript" > var onloadCallback = function () {         grecaptcha . render ( 'html_element' ، { 'sitekey' : 'your_site_key' })؛ }؛ </script> </head> <body> <form action = "؟" method = "POST" > <
  
    
     
        
 
            
        
      
    
  
  
      
       > </div> <br> <input type = "submit" value = "Submit" > </form> <script src = "https://www.google.com/recaptcha/api.js؟ onload = onloadCallback & render = صريح " تأجيل غير متزامن > </script> </body> </html>
      
        
    
     
         
    
  <html> <head> <title> reCAPTCHA demo: تقديم صريح للعديد من الأدوات المصغّرة </ title> <script type = "text / javascript" > var checkCallback = function ( response ) {         alert ( response )؛ }؛ فار widgetId1 ؛ فار widgetId2 ؛ var onloadCallback = function () { // يعرض عنصر HTML بمعرف 'example1' باعتباره عنصر واجهة تعامل reCAPTCHA. // يتم تعيين معرف عنصر واجهة تعامل reCAPTCHA إلى 'widgetId1'.
  
    
     
        

      
      
      
        
        
        
        widgetId1 = grecaptcha . تقديم ( 'example1' ، { 'sitekey' : 'your_site_key' ، 'theme' : 'light' }) ؛         widgetId2 = grecaptcha . render ( document . getElementById ( 'example2' )، { 'sitekey' : 'your_site_key' })؛         grecaptcha . تقديم ( 'example3' ، { 'sitekey' : ' 
            
            
        
 
            
        
 
            
          'رد الاتصال' : checkCallback ، 'theme' : 'dark' })؛ }؛ </script> </head> <body> <! - يتم عرض سلسلة استجابة g-recaptcha في رسالة تنبيه عند الإرسال. -> <form action = "javascript: alert (grecaptcha.getResponse (widgetId1)) ؛" > <div id = "example1" > </div> <br> <input type = "submit" value = "getResponse" > </form> <br> <! - إعادة تعيين reCAPTCHA widgetId2 عند الإرسال. -> < عمل الشكل = 
            
        
      
    
  
  
    
     
       
      
        
    
    
    
     "جافا سكريبت: grecaptcha.reset (widgetId2)؛" > <div id = "example2" > </div> <br> <input type = "submit" value = "reset" > </form> <br> <! - إعادة النشر إلى عنوان URL للصفحة عند الإرسال مع g-recaptcha استجابة POST المعلمة. -> <form action = "؟" method = "POST" > <div id = "example3" > </div> <br> <input type = "
       
      
        
    
    
    
      
       
      
        
    
    <script src = "https://www.google.com/recaptcha/api.js؟onload=onloadCallback&render=explicit" async defer > </script> </body> </html> 
         
    
  
