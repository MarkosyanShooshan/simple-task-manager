Simple Task Management System 📝📌

[Armenian] Սա Python լեզվով գրված հրամանային տողի (CLI) պարզ ծրագիր է, որը նախատեսված է օրվա առաջադրանքները 
(tasks) կառավարելու համար: Ծրագիրն օգտագործում է հիմնարար Python կառուցվածքներ (դիկշնարի, ֆունկցիաներ, ցիկլեր)
և թույլ է տալիս ավելացնել առաջադրանքներ՝ նշելով դրանց կարևորությունը, դիտել ակտիվ ցուցակը և ջնջել կատարված 
առաջադրանքները:

[English] This is a lightweight and interactive command-line (CLI) Task Management application built with 
Python. It utilizes fundamental programming structures (dictionaries, functions, and control loops) to allow 
users to add tasks with specific priority levels (High, Medium, Low), view the active task list, and delete 
completed tasks.


 Features

* Առաջադրանքների ավելացում (Add Tasks): Յուրաքանչյուր առաջադրանք պահվում է Python dictionary-ում՝ իր
  կարևորության աստիճանի հետ միասին (High, Medium, Low):
* Ցուցակի դիտում (View Tasks): Բոլոր ակտիվ առաջադրանքների կոկիկ արտապատկերում:
* Անվտանգ ջնջում (Delete Tasks): Հնարավորություն է տալիս հեշտությամբ ջնջել առաջադրանքը ըստ անվանման, եթե այն
  արդեն կատարվել է:
* Տվյալների սրբագրում (Data Sanitization):** Օգտագործում է `.strip()` և `.capitalize()` մեթոդները՝ օգտատիրոջ
  պատահական տառասխալները և ավելորդ բացատները կանխելու համար:
