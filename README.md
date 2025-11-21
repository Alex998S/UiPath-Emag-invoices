# Order Invoice Downloader

The autotamion is used to store all the products ordered into an excel sheet and donwload the coresponding invoices from an online shopping website.

The automation makes use of Orchestrator assets (named ```LogInCredentials```), to store the log in credentials and storage buckets (```Invoices``` and ```OrdersSheet```) to store the saved invoices and excel file with all the orders.


Final sheet with all the products ordered:

<img width="654" height="216" alt="Screenshot 2025-11-21 075612" src="https://github.com/user-attachments/assets/8a5d08aa-65fd-4bff-9cbd-986613877554" />



Overview of the ```Main.xaml``` workflow:

<img width="607" height="638" alt="Screenshot 2025-11-21 073944" src="https://github.com/user-attachments/assets/2fb082a1-8193-4cdb-b344-a7dccd16df76" />

## Features missing that are going to be added
- an excel montly chart showing how much has been spent
