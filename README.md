DECLARE  	a int; 
b int; BEGIN  	
a := 10;  
b := 20;  	
if(a>b) then  
dbms_output.put_line(‘a is greater than b’);  
elsif(b>a) then  	
dbms_output.put_line(‘b is greater than a’); 
	 	else 
 	 	dbms_output.put_line(‘Both a and b are equal’);  	end if; 
END; 
/ 
