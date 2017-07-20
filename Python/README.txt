* Copyright (c) 1998, Regents of the University of California
* All rights reserved.
* Redistribution and use in source and binary forms, with or without
* modification, are permitted provided that the following conditions are met:
*
*     * Redistributions of source code must retain the above copyright
*       notice, this list of conditions and the following disclaimer.
*     * Redistributions in binary form must reproduce the above copyright
*       notice, this list of conditions and the following disclaimer in the
*       documentation and/or other materials provided with the distribution.
*     * Neither the name of the University of California, Berkeley nor the
*       names of its contributors may be used to endorse or promote products
*       derived from this software without specific prior written permission.
*
* THIS SOFTWARE IS PROVIDED BY THE REGENTS AND CONTRIBUTORS "AS IS" AND ANY
* EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
* WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
* DISCLAIMED. IN NO EVENT SHALL THE REGENTS AND CONTRIBUTORS BE LIABLE FOR ANY
* DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
* (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
* LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
* ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
* (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
* SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Python version: 3.5
Author: Meng Deng
Instruction to run the python code:
	1. Logistic Regression, SVM, NBC implementation and evaluation
	2. Random Forest, bagging, and boosted trees implementation and evaluation
* The preprocessing function is not included in files. They are process_str, read_dataset, 
  get_most_commons, and generate_vectors. Users should form their own version of string
  preprocessing files, and output vectors of binary features. 
* To compare Logistic Regression, SVM, and NBC models, I tuned the following parameters to 
  analyze the model performances:
	1. Training sample size: [1%, 3%, 5%, 8%, 10%, 15%] of the total sample size.
	2. Feature number: default is 4000.
* To compare ensemble models including Random Forest, Bagging, and boosted trees, I tuned the 
  parameters to analyze the model performances:
	1. Training sample size: [2.5%, 5%, 12.5%, 25%] of the total sample size.
	2. Feature number: [200, 500, 1000, 1500]
	3. max tree depth: [5, 10, 15, 20]
	4. tree number: [10, 25, 50, 100]
* The results of all the comparison can be found in the results folder. }
