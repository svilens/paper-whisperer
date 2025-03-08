# [Paper Whisperer](https://huggingface.co/spaces/paper-whisperer/paper-whisperer)


🎙️ Welcome to [The Paper Whisperer](https://huggingface.co/spaces/paper-whisperer/paper-whisperer) — your gateway to unlocking the world of science through engaging, insightful, and easy-to-follow discussions.

✨ Hosted by Dr. Caspian Neuralforge , each episode features in-depth reviews of groundbreaking scientific papers. Together with the paper's author, they break down complex research into lively, accessible conversations. Whether you're a researcher, a student, or simply curious about the latest discoveries, this podcast offers a unique window into the minds behind the science.

🔭 Join us and explore the world of research like never before!

---

*The Paper Whisperer is a tool that converts any research paper from Arxiv.org into an engaging and informative podcast. It was developed during an AI hackathon organized by [AI Engineer Foundation Europe](https://lu.ma/aief-europe) and is currently available at [HuggingFace Spaces](https://huggingface.co/spaces/paper-whisperer/paper-whisperer).*

The user selects a paper from the most recent ones in the selected science category. The paper is parsed into XML and the process flow splits into 3 parts where an LLM comes into play:
- summary generation
- questions generation
- answers generation

The questions and answers are generated iteratively and as soon as each one is ready, it is passed to a text-to-speech model. This avoids the need to wait until the whole conversation is pre-generated in full - you will actually start listening as soon as each utterance is ready!

![Paper Whisperer](https://i.ibb.co/hV95TGs/paper-whisperer.png)
