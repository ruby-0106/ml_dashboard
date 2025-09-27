# ml_dashboard(Individual Project)
Machine Learning Prediction Project with Power BI insight dashboard

**Dataset**: Bank Marketing Campagin Dataset(cleaned) 
**Output**: 1/ Predict will the cilent buy the deposit or not
        2/ PowerBI dashboard for insights of the dataset 
**Tools**: Jupyter Notebook, PowerBI
**Pandas, Random Forest Machine Learning Model.**

**Working Process**: For the prediction, the dataset is cleaned and I made sure that there is no null values, duplicates and typos. For that, I quickly checked by using pandas.
                    After that, I chose client information attributes since there are mandatory data for every client. 
                    X = # X for predictor features, df[['age', 'balance', 'loan_num', 'housing_num', 'default_num', 'education_num', 'marital_num']], in here, you can see some columns are in **_num** in name 
                    because I changed from their **yes/no** data values or **object data-type** to int and numerical to make prediction. 
                    Y = Target feature, will be the deposit column **(outcome, yes/no)**


                    Then, using random forest model, I trained and tested the dataset.
                    The accuracy is 0.736582129165438.

                    Then I added a new client record, and then made the prediction. 


For the dashboard, I used powerbi. 


The **insights** from that: 


**(1)** Conversion Rate is 11.7 % 


**(2)** Sale Volume *Count* is 5,289.


**(3)** Top Deposit Clients:


                aged: 25-40,  

                
                job: Management, Technician, Blue-collar, 

                
                marital status: Single, Married, 

                
                education: Secondary & Tertiary 

                
**(4)** Clients who have 
✅personal loan-> ❌deposit(least likely) 


**(5)** Clients who have✅housing loan   ->  ✅deposit(possible) 


**(6)** Clients’ large yearly balance doesn’t mean they made a high deposit 


**(7)** Next Campaign should reduce contacting to the clients and the duration of contacts. 


**(8)** During the next campaign, contacting to the clients with cellular type is strongly 
recommended. 


**(9)** From April to August is the best period to offer term deposit to the clients. 


**(10)** Current Campaign attracted many new deposit clients and re-contacting recent 
clients also boosted deposit sales.


**(11)** Previous campaign has effects on the current campaign and this current campaign 
could turn the failed results from the previous into success. 


 **Data for better analysis:**
▪ Deposit amount in numbers
▪ Unknown Data values
▪ What kind of contact types more specific 
(eg. Phone call, email, SMS Text Message, In-app notification) 

For the further insight for my work process and thinking, recommend you to check in the file named **"bankMarketing_dataset_dashboard"** and **"bankMarketing_dataset_ prediction"**. Please **Download those files first** in order to view the process. 
   There, I explained details steps how I worked with the data.
   
   Thank you!! 😉

                    
