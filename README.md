# Customer Support Agent Tutorial Episode 5

In this final part of the tutorial series, we added on customer and order management to complete the proof of concept chatbot. Customers can now:

- View existing orders
- Create new orders and update the relevant 'databases'

Take a look at the bottom half of the below diagram to see what we will build:

![Blank diagram (15)](https://github.com/user-attachments/assets/62305fcb-3414-41a2-9e2d-8f306219ccc0)

Here is what one of the final customer journeys look like:

![image](https://github.com/user-attachments/assets/8230d153-22d4-422d-9746-afbeda7ba69c)


## Setup

To setup the python environment I did:

```bash
conda create -p ./.conda python=3.11
pip install -r requirements.txt
```

Then activated the environment with:
```bash
conda activate ./.conda
```

To run the frontend you can type:

```bash
streamlit run streamlit_frontend.py
```

Happy Agent Building :D
