# Uthuru Mithuru

##  Augmentative and Alternative Communication (AAC) companion


https://asangikak.github.io/website_uthuru_mithuru/

Key Features:

    - Text To Speech
    - In built Next Word predictions


Cost:

    This App was designed as a trial for a pilot project. I have kept the costs as low as possible for the MVP.
    However, there are some cloud costs.Such as
        - API requests.
        - Google Developer Account.
        - software maintenance costs.
    Hence, I am unable to give unlimited access.

In built Word prediction model:

    Next-word prediction, similar in concept to the autocomplete feature on a phone keyboard.
    My goal is simply to run predictions from a trained statistical model in a Flutter app. Ship the model trained 
    using sample data then to improve/fine tune on user data.
    
    Since the dataset is small(~200 unique words), advanced features such as LSTM training were not considered.
    This is essentially a Markov chain or an n-gram language model. It has several advantages for this use case:
    • Learns instantly from new user input (no retraining).
    • Tiny memory footprint (often smaller than a neural network).
    • Easy to inspect and debug.
    • Very fast on-device.
    • Naturally incorporates user-specific words.
    • On-device personalization.
    • Privacy is important.

     Base Language Model → created before the app ships is a cold-start model. It is an n-gram prediction model.

    - The AI model has only been developed and tested in an isolated Python development environment. (0 cost)

N - gram prediction model
https://github.com/asangikak/aac_model_builder_phase3

    
    

    
    