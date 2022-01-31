# Golang_Template


# ATTENTION :=  we are discussing about  'text/template'  not about 'html/template'
# ===================================================================================


![image](https://user-images.githubusercontent.com/80065996/151787735-1ec56112-7eea-48a9-8694-eb6952986e6a.png)


# Above simple example of template where we mentioned the field name of 'Person' struct inside the parse function so that when we execute the template with the struct object 
# it will get picked up and replace the placeholder value 

# result:


![image](https://user-images.githubusercontent.com/80065996/151788294-da66bf34-22d8-45bb-b5f6-a4b3bfe332aa.png)


# ranging the values using the template


![image](https://user-images.githubusercontent.com/80065996/151793600-83d2c3c4-ba0d-42c1-933c-4d5343a64c09.png)


![image](https://user-images.githubusercontent.com/80065996/151793646-69537e62-23c5-4ed2-acc0-5941ef7df214.png)


![image](https://user-images.githubusercontent.com/80065996/151793691-86c39b75-862d-49c7-a556-e87d7f915bae.png)


![image](https://user-images.githubusercontent.com/80065996/151793743-a9f98aab-1f84-434f-a98c-19bd999f3598.png)


![image](https://user-images.githubusercontent.com/80065996/151793909-41d4bcc4-425d-40b5-81c9-9739e364772c.png)


# Range can also be used along with {{ with }}


![image](https://user-images.githubusercontent.com/80065996/151794045-dc10dc69-0c03-47d1-967d-08370f4a5d19.png)


![image](https://user-images.githubusercontent.com/80065996/151794103-06f9a85c-5b1e-4599-b915-2346583fb124.png)


# conditional statements 
# simple 'if' statement


![image](https://user-images.githubusercontent.com/80065996/151796446-8225a71e-6fa1-4a36-95c5-6a550df51025.png)


![image](https://user-images.githubusercontent.com/80065996/151797813-41c9db77-a28f-4cf1-a60c-4ec831b57829.png)


![image](https://user-images.githubusercontent.com/80065996/151797925-72e61c2a-7315-4e2c-9317-c1e5fbf6e0a5.png)


![image](https://user-images.githubusercontent.com/80065996/151798258-149cabe6-0bb6-44b4-86a4-3fab2b20700f.png)


![image](https://user-images.githubusercontent.com/80065996/151797974-d08feb23-4f88-41f0-9e93-4c763dcc2e70.png)


![image](https://user-images.githubusercontent.com/80065996/151798489-c55d1b8d-47e7-45c4-8305-aaa74eda4788.png)


# if we use only dot (.) when u use struct the entire object will be displayed in the placeholder.


![image](https://user-images.githubusercontent.com/80065996/151807491-29b797a6-27c6-4def-bc7e-88c512551096.png)


![image](https://user-images.githubusercontent.com/80065996/151810526-427b1fa9-0dc6-4b88-bb48-80b748fe6b0a.png)


# using dot(.) for variable instead of struct and it displayed empty value. 


![image](https://user-images.githubusercontent.com/80065996/151811248-72a5079e-a575-480e-9f1a-bb97a0d81aba.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/151811553-cab9c605-78eb-4fc7-aaf0-993f0ec409b7.png)


![image](https://user-images.githubusercontent.com/80065996/151811614-8d853c54-90ba-4c26-bb4c-2124ca213d92.png)


![image](https://user-images.githubusercontent.com/80065996/151811659-7487d80e-a76e-45d2-a42b-873fff3b5dc8.png)


# Comment in the template


![image](https://user-images.githubusercontent.com/80065996/151818379-25ef8e82-ac48-43b4-a17f-a1d8d3b91389.png)


# conditional operator
# now the struct is having values. so 'T1' will be executed


![image](https://user-images.githubusercontent.com/80065996/151820496-f603454a-b647-4b01-9427-d7384f0dd6e8.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/151820776-c784a026-ed96-4c50-bdf0-72cea9bde198.png)


# now changing the values of struct object

# making ag field as zero


![image](https://user-images.githubusercontent.com/80065996/151820897-0e85469a-f144-4d40-a0c4-02732f100b0c.png)


![image](https://user-images.githubusercontent.com/80065996/151820974-39c3d5bf-7ff1-400b-a414-056203bb3fb4.png)


![image](https://user-images.githubusercontent.com/80065996/151821029-9067964f-c7f0-49a5-bcd1-22ea6b364100.png)


# making 'name' field as 'spaces'


![image](https://user-images.githubusercontent.com/80065996/151821157-27ad3243-79c6-4f12-826f-bc74c4d5eb25.png)


# only one T1 printed for Age field


![image](https://user-images.githubusercontent.com/80065996/151821280-25fc1003-4dc5-45bb-807c-99fa10e9f34a.png)


# If else condition


![image](https://user-images.githubusercontent.com/80065996/151821616-d2ff5d22-0634-4b15-9bbc-e24a15f20862.png)


# Result


![image](https://user-images.githubusercontent.com/80065996/151821670-64175005-d600-465f-8a52-dab77cfc81d4.png)


# another example,


![image](https://user-images.githubusercontent.com/80065996/151821836-c034f200-8fef-44a9-91e9-ec7fc03e6051.png)


![image](https://user-images.githubusercontent.com/80065996/151821894-d5d2d606-b660-4e5e-9f78-021e46eaa97c.png)


# if else and else if condition


![image](https://user-images.githubusercontent.com/80065996/151822296-91e6dfe1-1e08-424c-9a19-9f3cecb8a025.png)


![image](https://user-images.githubusercontent.com/80065996/151822394-bd8ef336-aa62-4345-8e33-3ba91ea26109.png)



![image](https://user-images.githubusercontent.com/80065996/151822354-693283f4-9a48-42e2-8bf6-50c2b9211f96.png)



![image](https://user-images.githubusercontent.com/80065996/151822754-cdda958a-0563-4242-aef7-110b5dc1a4a8.png)


![image](https://user-images.githubusercontent.com/80065996/151822786-a46d63a3-2355-403e-af6d-973976dff4be.png)


# Example,


![image](https://user-images.githubusercontent.com/80065996/151838578-8e2e55c4-0498-4df0-9607-c2e4711b1c32.png)


![image](https://user-images.githubusercontent.com/80065996/151838629-9c3e6dd7-1ceb-432e-853b-13d2cdd8c195.png)


![image](https://user-images.githubusercontent.com/80065996/151838676-a27b6677-d756-411f-89ed-48f3d356d065.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/151838755-6e22be1f-d975-4f69-8788-dc70c6476bd3.png)


# Another example with approach along with 'buffer'


![image](https://user-images.githubusercontent.com/80065996/151841872-499bc42b-2afd-48b6-ad58-ad4a594cd0e1.png)


![image](https://user-images.githubusercontent.com/80065996/151841970-16657552-7c53-4601-bde9-a5ed0c008b9a.png)


# Result:


![image](https://user-images.githubusercontent.com/80065996/151842019-7e5e399c-2ec1-4154-9480-a3d1f1f2b325.png)


# Logical operators in go html template


![image](https://user-images.githubusercontent.com/80065996/151842236-c06dbbca-edce-4b47-9426-2dd9176ee654.png)



