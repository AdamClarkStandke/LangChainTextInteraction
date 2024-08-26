# LangChainTextInteraction
Using Langchain, LLMs, and Promt Templates to interact with (primarily) scientific based text documents for answering questions (QA).

# Results:
Given the following context as found here [BeyonVisualLineofSight](https://huggingface.co/datasets/SammyTime/plaything/blob/main/play.txt)
and the following Question: Define VLOS EVLOS BVLOS 

Two text generation models answer the question as follows 

## Model: mistralai/mistralai/Mistral-7B-Instruct-v0.2
Question: Define VLOS EVLOS BVLOS 

Answer:
VLOS stands for Visual Line of Sight, which refers to the ability to see an unmanned aerial vehicle (UAV or drone) directly from the ground without any obstruction. This means that the person operating the drone maintains a clear view of it throughout the flight.

EVLOS stands for Extended Visual Line of Sight, which extends the range of direct visual observation beyond the normal VLOS limit. It typically involves the use of video downlinks or other communication systems to maintain real-time visual contact with the drone while it flies further away.

BVLOS stands for Beyond Visual Line of Sight, which goes beyond both VLOS and EVLOS ranges. In this mode, the drone operates outside the operator's direct line of sight, often relying on advanced technologies like sensors, artificial intelligence, and automated systems to ensure safety and effective operation.

max_new_tokens=512, top_p=0.95, typical_p=0.95, temperature=0.1, repetition_penalty=1.2, return_full_text=True, seed=42

## Model: tiiuae/tiiuae/falcon-7b-instruct
Question: Define VLOS EVLOS BVLOS 

VLOS (Very Low-Altitude Operations) is a type of UAS (Unmanned Aerial System) that is designed to fly at altitudes below 400 feet. It is typically used for surveillance, mapping, and other similar purposes. EVLOS (Extreme Low-Altitude Operations) is a type of UAS that is designed to fly at altitudes below 200 feet. It is typically used for BVLOS (Beyond Visual Line of Sight) operations, which involve flying a UAS beyond the visual line of sight of a human operator.

max_new_tokens=512, top_p=0.95, typical_p=0.95, temperature=0.1, repetition_penalty=1.2, return_full_text=True, seed=42





