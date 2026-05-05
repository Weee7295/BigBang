# Big Bang Number Generator

This repository contains a JavaScript solution for a sequence prediction model based on prime number collisions. The script generates an array of 100 elements, replacing specific numbers based on their divisibility by 3 and 5, and exports the result to a JSON file.

## Project Description

The model iterates through numbers 1 to 100 with the following logic:
* Numbers divisible by **3** are replaced with **"BIG"**.
* Numbers divisible by **5** are replaced with **"BANG"**.
* Numbers divisible by **both 3 and 5** are replaced with **"BIGBANG"**.
* All other numbers remain as strings.

## Prerequisites

* [Node.js](https://nodejs.org/) (Recommended version: 14.x or higher)

## Setup and Execution

### Step 1: Clone or Download
Clone this repository to your local machine or download the source files into a folder.
```bash
git clone <your-repository-url>
cd <repository-name>

### Step 2: Run the Script
Open your terminal or command prompt in the project's root directory and execute the script using Node.js:
```bash
node script.js

## Output Description

After executing the script, a file titled **`output.json`** will be generated in the project root directory. This file contains the final results of the prime collision model.

### Sample Result
The content of `output.json` will be structured as follows:

```json
[
  "1",
  "2",
  "BIG",
  "4",
  "BANG",
  "BIG",
  "7",
  "8",
  "BIG",
  "BANG",
  "11",
  "BIG",
  "13",
  "14",
  "BIGBANG"
]