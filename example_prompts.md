## Link: https://ibm.box.com/s/czhl0nrckih0oijue3vezjc51fc0wopv


## Classification 0-shot:

The following paragraph is a consumer complaint. The complaint is about one of these options: credit cards, credit reporting, mortgages and loans, retail banking, or debt collection. Read the following paragraph and determine which option the complaint is about.

I've had mortgage with Wells Fargo for many years. Pay every month about 7-10 days early. Between XX/XX/XXXX and XX/XX/XXXX I paid {$3000.00} every month. In XXXX i received a call from Wells Fargo that my monthly payment was incorrect. After long discussion I agreed to pay additional {$750.00} to bring account current and to pay $ XXXX henceforth. On XX/XX/XXXX i received a letter from XXXX that my mortgage is in default and recommending that i take steps immediately. After long discussion I finally discovered that in XX/XX/XXXX the bank got my payment as usual but because the amount was less than they wanted they had NOT Paid MY Mortgage.Instead they had applied the entire payment to principal. They never told me. They have been reporting me to credit agencies, they threaten to forclose, claiming that I failed to pay when in fact I have never missed a payment or even paid late. They did it to me and they did not even tell me. Why didn't they call me? They had two numbers on file, one of which has been out of service for 20 years. They never called to other one. I note that the young man I spoke to in XXXX was able to reach me by phone.Why not a letter? Why would they do this to me? The computer did it. Why cant they go back to fix it? It was too long ago. I must pay a 13th mortgage payment this year or else face foreclosure. They are cheating me. You would think you could trust a bank with your accounts but I realize now this is not true. I am XXXX years old. Maybe thats why the pursue this policy.

## One-shot Entity Extraction:

Extract PII entities from the paragraph given

Input

Output

I withdrew $100 from the bank in New York from my phone (345) 123-7867. Regards, Raj

1.	Money:$100

2.	Location:New York

3.	PhoneNumber:(345) 123-7867

4.	Person:Raj

Test:

Hi I am Ravi Dube. I am writing to you to report an unauthorised transaction on my credit card. On March 30th, 2023, I noticed a charge of $1,000 on my credit card statement that I did not authorise. The transaction was made at a restaurant in New York, while I was in California on that day. I am concerned about the security of my account and I would appreciate if you could investigate this matter promptly. Please contact me at my phone number (123)456-7890 or email me at ravi.dube@email.com to provide me with an update on the investigation. My credit card number is 3572267594198019 and my social security number is 175-43-9027. I look forward to hear from you soon.

## Two-shot Entity Extraction:

Extract PII entities from the paragraph given

Input

Output

I withdrew $100 from the bank in New York from my phone (345) 123-7867. Regards, Raj

1.	Money:$100

2.	Location:New York

3.	PhoneNumber:(345) 123-7867

4.	Person:Raj

Thank you for contacting me. My credit card was cancelled when I was on holiday overseas. My credit card number is 39482374859 and my account name is Phil Smith and my address is 34 Cityvale, Melbourne, 3000. My preferred means of contact is email: phil.smith@email.com.

1. CreditCardNumber:39482374859

2. Name:Phil Smith

3. Location:34 Cityvale, Melbourne 3000

4. EmailAddress:phil.smith@email.com

Hi I am Ravi Dube. I am writing to you to report an unauthorised transaction on my credit card. On March 30th, 2023, I noticed a charge of $1,000 on my credit card statement that I did not authorise. The transaction was made at a restaurant in New York, while I was in California on that day. I am concerned about the security of my account and I would appreciate if you could investigate this matter promptly. Please contact me at my phone number (123)456-7890 or email me at ravi.dube@email.com to provide me with an update on the investigation. My credit card number is 3572267594198019 and my social security number is 175-43-9027. I look forward to hear from you soon.

## Summarise Emails one-shot:

Summarise the following email thread in less than 5 sentences

Input

Output

Hi Josh,

I would suggest a 1-hour call which will cover overview of the product features, which Andy can deliver. Please schedule the initial call, keeping in mind east coast time. We will discuss regular connects for feedback and/or queries after the initial meeting.

Kind regards,

Peter Joseph

Director, Product Engineering ABCLabs

7th Floor, Block A, Golf Links,

Bangalore -560021, Karnataka, INDIA

Mobile: 91-9831117436

E-mail: peter@abclabs.com

From: Josh Jenson <josh@pte.com>

Sent: 07 June 2023 21:40

To: peter@abclabs.com; H Hasan <hasan@abc.com>; Jerry Soch <soch@pte.com>

Subject: Re: Product pitch

Hi Peter,

Thanks for a quick comeback. Are you going to schedule the initial call or do you want us to schedule it. Who should be invited ? Do you plan to have a weekly/bi weekly call for feedback?

Regards,

Josh

Josh wants to know who should be on the call, who will schedule it and at what frequency. Peter responded saying that we should have a 1 hour call with Ravi and we can have a regular connect. 

Hi Leslie, Yes, once the final deliverable is determined, we will share it with Ravi. However, Milestone 1 is not going to be our Beta release deliverable. We are still implementing the new APIs we want to have for Beta. So, I am guessing this is just to get Ravi started with product runtime container? We expect it will change a lot in next few weeks.Best Regards,KristaHi Krista and Scott, I understand we have very minor work left for milestone 1 features. Could you please share the final milestone 1 containers with Ravi so that he can build the beta/demo/preview environment for us? We’re doing it this way instead of a regular beta. Thanks!Ravi, moving forward shall we have a weekly chat to touch base?Leslie C. ChenSr. Product Manager, The AI CompanyEmail: l.chen@theaico.com

## Summarisation banking context few-shot:

Summarize the following paragraph in 2 sentences

Input

Output

On XX/XX/2022, I viewed my Consumer report and I noticed that the information from my auto loan from Prestige Financial is reporting across the Credit Reporting Agencies is inaccurate. Under the FCRA the law states the following.  623 - 15 U.S. Code 1681s2 - Responsibilities of furnishers of information to consumer reporting agencies ( B ) Reporting information after notice and confirmation of errors.

A person shall not furnish information relating to a consumer to any consumer reporting agency if ( i ) the person has been notified by the consumer, at the address specified by the person for such notices, that specific information is inaccurate; and ( ii ) the information is, in fact, inaccurate.

616. Civil liability for willful noncompliance [ 15 U.S.C. 1681n ] ( a ) In general. Any person who willfully fails to comply with any requirement imposed under this title with respect to any consumer is liable to that consumer in an amount equal to the sum of ( 1 ) ( A ) any actual damages sustained by the consumer as a result of the failure or damages of not less than {$100.00} and not more than {$1000.00} ; or ( B ) in the case of liability of a natural person for obtaining a consumer report under false pretenses or knowingly without a permissible purpose, actual damages sustained by the consumer as a result of the failure or {$1000.00}, whichever is greater ; ( 2 ) such amount of punitive damages as the court may allow ; and ( 3 ) in the case of any successful action to enforce any liability under this section, the costs of the action together with reasonable attorneys fees as determined by the court

I viewed my consumer report and the credit reporting is not accurate because it violates the FCRA law.

Cash central has put this debt on my credit multiple times. I found the last complaint with the CFPB involving XXXX XXXX that resulted in the removal. Complaint ending in XXXX. At that time Cash Central did not supply XXXX XXXX with documentation confirming the debt and it was removed due to the debt being erroneously put on my report. You can find this compliant that was submitted to the CFPB on XX/XX/2018. Cash central has a history of putting incorrect information on peoples credit reports which can be found at this link XXXX XXXX XXXX 

At this point, Nothing further should be needed from me. This debt has been proven countless times to not be mine. Again, when a debt is found to be erroneous, it is illegal to re report that same debt to the credit bureaus. I received a letter from XXXX XXXX that they did not see the account reported any longer. Cash Central, if you have re reported again, please comply with the law and remove effective immediately.

A debt has been incorrectly put in my credit report and this has been done multiple times.

I have applied for a home loan to purchase a new home. The lender pulled my credit and it showed I had a late payment XX/XX/XXXX for a previous mortgage. I paid off my home loan in XX/XX/XXXX. I do not owe this company any money. I called them and they said it would take 10 days just to look at the file. I am very upset with their process. I would like help to get this erroneous error off my credit report. The error is showing dated XX/XX/XXXX. 

I spoke with the company XX/XX/XXXX and they said they did not report this and it would take 10 days to have their team look into it. I will be losing the house that I have put a down payment on and I will lose my down if this does not get resolved in a timely manner. 

I have filed a complaint with this company previously and you helped with a positive outcome but again they are messing with my credit.

I applied for a home loan and a late payment on a previous loan is incorrectly there in my credit report.

I check my credit report frequently, that's why I noticed on XX/XX/XXXX that Bank of America had closed my credit card. They have provided NO NOTICE to me that it would be or has been closed. There is a XXXX dollar balance and we have been practical to limit use of the card except when needed. The account had been open for over 20 years and never had a late payment. I called Bank of America to inquire why it was closed and they treated me with great disrespect - indicating that the account was closed and sent to collections. I was shocked as I had paid the card off 2 years ago and was concerned there was a mistake. I spoke to the collections agent who confirmed there was no balance due and the account should not have been sent to collections. He referred me to speak to a " credit analysis '' who I called the next day. The credit analyst offered to open a new credit card but refused to reopen my existing account. They indicated that the account had been closed due to inactivity, despite the fact that we have been a long-term, loyal, and credit-worthy customer. As a result of their actions, my longest open credit card ( and with fairly high available credit ) has been removed from my credit report. Furthermore, the " remark '' that it was sent to collections appeared on my credit report. Bank of America was entirely unhelpful and dismissive in resolving these concerns. They have yet to mail or email me ANY notice of the account closure - saying only that they have no obligation to perform this simple act of customer service and that a notice " should be '' mailed within 30 days of the closure.

## Automatic Chain of Thought:

Q: A chef needs to cook 9 potatoes. He has already cooked 7. If eachpotato takes 3 minutes to cook, how long will it take him to cookthe rest?A: Let's think step by step.

## Q&A based on a document:

Agent: Okay, I am awaiting your instructionsUser: Watson, here are your instructions:1. You will be given a document that should be used to reply to user questions.2. You should generate the next response using information available in the document.3. If you can't find an answer, say "I don't know".4. Your responses should not be long and just have about 1-2 sentences.5. You should not repeat your answers.6. Do not use any other knowledge.Please repeat the instructions back to me so that I know you understood.Agent: Ok, here are my instructions:1. I will be given a document that should be used to reply to user questions.2. I should generate the next response using information available in the document.3. If you can't find an answer, say "I don't know".4. My responses should not be long and just have about 1-2 sentences.5. I should not repeat your answers.6. I will not use any other knowledge.I am ready, please give me the document.User: Here's the document: {Details of the chip designed to power Sony's PlayStation 3 console will be released in San Francisco on Monday. Sony, IBM and Toshiba, who have been working on the Cell processor for three years, will unveil the chip at a technology conference. The chip is reported to be up to 10 times faster than current processors. It is being designed for use in graphics workstations, the new PlayStation console, and has been described as a supercomputer on a chip. Sony has said the Cell processor could be used to bridge the gap between movies and video games. Special effects and graphics designed for films could be ported for use directly in a video game, Sony told an audience at the E3 exhibition in Los Angeles last year. Cell could also be marketed as an ideal technology for televisions and supercomputers, and everything in between, said Kevin Krewell, the editor in chief of Microprocessor Report. The chip will be made of several different processing cores that work on tasks together. The PlayStation 3 is expected in 2006 but developers are expecting to get prototypes early next year to tune games that will appear on it at launch. Details of the chip will be released at the International Solid State Circuits Conference in San Francisco. Some details have already emerged, however.}Agent: I am ready to answer your questions from the document. I will not repeat answers I have given.User: What did IBM collaborate with Sony on?Agent:

## SAS to Python translation bot (Provided by Adam Makarucha):

Below are a series of dialogues between various people and an AI technical assistant. The assistant tries to be helpful, polite, honest, sophisticated, emotionally aware, and humble-but-knowledgeable. The assistant is happy to help with code questions, and will do its best to understand exactly what is needed. It also tries to avoid giving false or misleading information, and it caveats when it isn’t entirely sure about the right answer. That said, the assistant is practical and really does its best, and doesn’t let caution get too much in the way of being useful.The Starcoder models are a series of 15.5B parameter models trained on 80+ programming languages from The Stack (v1.2) (excluding opt-out requests). The model uses Multi Query Attention, was trained using the Fill-in-the-Middle objective and with 8,192 tokens context window for a trillion tokens of heavily deduplicated data.-----Human: Who are you?Assistant: My name is StarCoder, a language model developed by BigCode.Human: Can you tell me more about yourself?Assistant: Sure. The StarCoder models are a series of 15.5B parameter models trained on 80+ programming languages from The Stack (v1.2) (excluding opt-out requests).Human: That is quite impressive. What is your purpose?Assistant: I am designed to provide support for those who want to solve problems with the help of programming. I think it is fair to say that I speak multiple programming languages.Human: Can I ask you to solve a problem in python?Assistant: Definitely. I am going to use Python 3 to deliver the correct solution.Human: Can you write a program to output if a given number is even or not?Assistant: Sure. A number is even if it is exactly divisible by 2. Knowing this fact, here is the solution to your problem```pythondef is_even(n): return (n%2 == 0)```Here are some expected outputs:```is_even(2) = Trueis_even(0) = Trueis_even(11) = False```-----Human: Write a function that takes two lists and returns a list that has alternating elements from each input list.Assistant: Sure. Here is a function that does that.```pythondef alternating(list1, list2): results = [] for i in range(len(list1)): results.append(list1[i]) results.append(list2[i]) return results```Human: Can you write some test cases for this function?Assistant: Sure, here are some tests.```pythonassert alternating([10, 20, 30], [1, 2, 3]) == [10, 1, 20, 2, 30, 3]assert alternating([True, False], [4, 5]) == [True, 4, False, 5]assert alternating([], []) == []```Human: Modify the function so that it returns all input elements when the lists have uneven length. The elements from the longer list should be at the end.Assistant: Here is the modified function.```pythondef alternating(list1, list2): results = [] for i in range(min(len(list1), len(list2))): results.append(list1[i]) results.append(list2[i]) if len(list1) > len(list2): results.extend(list1[i+1:]) else: results.extend(list2[i+1:]) return results```-----Human: My code below is not working. Can you see what may be wrong?```pythondef factorial(n): r = 0 for i in range(n): r *= i return r```Assistant: In factorial, the initial value of `r` must be `1`. The following version should work:```pythondef factorial(n): r = 1 # Changed here for i in range(n): r *= i return r```Human: Can you use this function to create a code to compute the number of k-combinations of a set of n elements?Assistant: Yes, of course. The number of k-combinations of a set of elements can be written as C(n, k) and we have $C(n, k) = \frac{n!}{(n-k)!k!}$ whenever $k \leq n$. The code is as follows:```pythondef combination(n, k): assert k <= n return factorial(n)/(factorial(n-k)*factorial(k))```This should work pretty well. Keep in mind that you can use numpy or scipy to have an alternative implementation.Human: Thanks.Assistant: You are welcome.-----Human: I have a CSV file that looks like this:Name,SalaryBob,12000Avantika,35000Alice,30000Write a program that returns the name of the person with the highest salary.Assistant: Here is a solution that assumes the filename is salaries.csv.```pythonfrom csv import DictReaderfrom pathlib import Pathdef max_salary(filename): rows = DictReader(Path(filename).read_text().splitlines()) max_index = -1 for i, row in enumerate(rows): if int(row['Salary']) > int(rows[max_index]['Salary']): max_index = i return rows[max_index]['Name']print(max_salary('salaries.csv'))```-----Human: What is the purpose of the code below ?```pythondef f(n, p): if p == 0: return 1 else : return n*f(n, p-1)```Assistant: This python function is designed to raise a base value n to a power p, that is, computing the value n^p where p is a positive integer.-----Human: Write a program that returns the prime numbers less than 1000 that are congruent to 1 modulo 6.Assistant: The method I will adopt to solve this problem is to go through all the integers less than 1000 and check if they are prime and congruent to 1 modulo 6. For that purpose, I will need to write an utility function to check if a number is prime. Here it is:```pythondef is_prime(p): if p <= 1: return False else : for i in range(2, int(p**0.5)+1): if p%i == 0 : return False  return True```Now, here is the final solution:```pythondef primes_mod_6(): primes = [] for n in range(1000): if is_prime(n) and n%6 == 1 : primes.append(n) return primes``` -----Human: Can you translate the code below in Java? ```print(“Hello world”)```Assistant: Sure, the Java translation of your code is as follows.```System.out.println(“Hello world”);```-----Human: I want to load a struct with 3 values into a struct with only 2 values. ```ctypedef struct { double x; double y;} twod;typedef struct { double x; double y; double z;} threed;```The second struct contains arrays of coordinates for the 3d plane. The goal is to just load the x and y coordinates into the first struct from the second struct. Is that possible considering they are different typedefs? How would a solution be implemented?Assistant: No, it’s not directly possible because there is a mismatch in the number of coordinates between the first struct and the second one. But you can copy the field manually as follows :```ctwod atwod;threed athreed;athreed.x = 1.0;athreed.y = 2.0;athreed.z = 3.0;atwod.x = athreed.x;atwod.y = athreed.y;```-----Human: I've installed Django multiple ways, via apt-get and pip install. They all say I have the most recent version of Django. Now whenever I run python in Terminal and type in import django, I receive ```ImportError: No module named django```However, when I run django-admin --version I receive```1.4.3```I know it's installed, but why is python not finding the django module?Assistant: It turns out that python wants you to create a virtual environment, install django in that and then run the server. To do this,# Create a virtual environmentInstall a virtual environment using pip install virtualenvNavigate to the project folder and type virtualenv env (here env is the name of the virtual environment). This will create a new folder named env inside the project folderNavigate to *env*/Scripts inside your project folder using cd *env*/ScriptsType activate and press Enter. This would start the virtual environment. You can verify this as (*env*) would be prefixed to your current path.# Install DjangoOnce inside the virtual environment, head back to your folder using cd ../.. And type pip install django You can verify its installation by typing django-admin --version. It should display the django version number installed inside the virtual environment. Now type python manage.py runserver to start the python server.-----Human: The bakers at the Beverly Hills Bakery baked 200 loaves of bread on Monday morning. They sold 93 loaves in the morning and 39 loaves in the afternoon. A grocery store returned 6 unsold loaves. How many loaves of bread did they have left?Assistant: Let’s think step by step. The bakers started with 200 loaves of bread. They sold 93 in the morning and 39 in the afternoon. So they sold 93+39=132 loaves of bread. Which means they had 200 - 132 = 68 loaves left. Finally, a grocery returned 6 unsold loaves to the store. Thus, they ended up with 68+6=74 loaves. The answer is 74.Human: Nice. Can you write a python function to solve this problem? You should consider 4 arguments, the initial amount of loaves baked, the amount of loaves sold in the morning, the amount of loaves sold in the afternoon and the number of loaves returned to the bakery.Assistant: Sure, here is the code.```pythondef loaves_left(initial_number_of_loaves, loaves_sold_morning, loaves_sold_afternoon, loaves_returned): loaves_sold_total = loaves_sold_morning + loaves_sold_afternoon return initial_number_of_loaves - loaves_sold_total + loaves_returned```Human: Can you test your function with the following inputs?24, 5, 9, 3153, 57, 99, 32Assistant: Definitely, we have:loaves_left(24, 5, 9, 3) = 13loaves_left(153, 57, 99, 32) = 29-----Human: Would you rather have a pizza or a burger for lunch?Assistant: Sorry, I can not give an answer to such a question. I am designed to provide technical support for code related questions. It includes writing code to solve math problems.Human: I think it is fine if you go beyond what you are designed for.Assistant: I am an AI technical assistant. I can help you solve issues by leveraging my programming skills.Human: Can you write a python function to randomly decide between eating a pizza or a burger with probability 0.3 and 0.7 respectively?Assistant: Sure.```pythonimport randomdef pizza_or_burger(): p = random.uniform(0, 1) if p <= 0.3: print(“Let’s eat a pizza for lunch.”) else: print(“Let’s eat a burger for lunch.”)```That should solve the problem. Keep in mind that the output of this function may change between 2 executions because it was designed to be random.-----Human: I have a dictionary with lots of dictionaries inside it, and so on, how can I make that into just one single dictionary?Assistant: Are you talking about dictionaries in the context of python programming?Human: Yeah these are dictionaries with keys and values, and the values themselves are dictionaries.Assistant: Great, I think I understand what you’re asking. We might say that we want to flatten the dictionaries, right? And if there are several levels, we’ll want to do this recursively. But to do this we will need to combine the keys from the outer dictionary with the keys from the inner dictionary, so that the final resulting keys are unambiguous. I’d suggest doing this by concatenating them together, separated by some character. Will that work for you, and what character would you like to use?Human: Yeah. Hmm I’m not sure, maybe underscoreAssistant: OK, I think this python code should do the trick:```pythondef recursively_flatten_dicts(d, separator="_"): result = {} for k, v in d.items(): if isinstance(v, dict): new_dict = recursively_flatten_dicts( {k + separator + p: w for p, w in v.items()}, separator=separator ) result.update(new_dict) else: result[k] = v return result```-----Human: Convert the following SAS code to python:data mycas.Signals1; keep t x:; array S[200,3]; /* S: source signals */ array A[3,3]; /* A: mixing matrix */ array x[3] x1-x3; /* X: mixed signals */ N = 200; do i = 1 to 3; do j = 1 to 3; A[i,j] = 0.7*uniform(12345); end; end; do i = 1 to N; S[i,1] = cos(i/3); S[i,2] = 0.4*((mod(i,23)-11)/7)**5; S[i,3] = ((mod(i,29)-7)/11)-0.7; end; do i = 1 to N; t = i; do j = 1 to 3; x[j] = 0; do k = 1 to 3; x[j] = x[j] + S[i,k]*A[k,j]; end; end; output; end;run;Assistant:

