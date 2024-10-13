Benchmark for evaluating the performance of the LLM model
=========================================================

Existing benchmarks can be divided into n categories :cite:`zheng2023judging` :

#. Core-knowledge benchmarks
#. Instruction-following benchmarks
#. Conversational benchmarks
#. Traditional evaluation metrics 

   - ROUGE :cite:`lin2004rouge` (:cite:year:`lin2004rouge`), BLEU :cite:`papineni2002bleu` (:cite:year:`papineni2002bleu`)

Open Source Benchmark
---------------------

#. taide-bench-eval

   - https://github.com/taide-taiwan/taide-bench-eval


#. :title-ref:`zheng2023judging` 
   
   - https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge

#. MMLU :cite:`hendrycks2020measuring`

#. HELM :cite:`liang2022holistic`

#. MT-bench :cite:`zheng2023judging`

#. Chatbot Arena :cite:`zheng2023judging`

Paper 
-----

#. :cite:year:`zheng2023judging` :title-ref:`zheng2023judging`
   
   - In this paper, the authors argue that the aligned model achieves better user preference, but the results cannot be accurately assessed by current benchmarks.
   
   - LLM-as-a-Judge 

      #. Pairwise comparison

         - Position Bias : LLM judges favor the first position

         - Verbosity Bias : LLM favors longer, verbose responses

         - Self-Enhancement Bias : LLM prefer the responses that generate by themselves

      #. Single answer grading

      #. Reference-guided grading
