# MTRB-QTA

Data-Efficient Massive Tool Retrieval: A Reinforcement Learning Approach for Query-Tool Alignment with Language Models

## Background

![Logo](./Images/Background.jpg)

The current approach to solving tool-based problems involves first addressing the (a) massive tool retrieval (MTR) task, followed by completing the (b) tool selection task. We focus on providing a solution for the MTR task. For evaluation, we introduce a new MTRB benchmark. Method-ologically, we propose a new QTA framework to enhance the retrieval systems by aligning user queries with tools.

## Overview

![Logo](./Images/QTA.jpg)

An overview of the proposed QTA framework, which includes data pipelines for the training and inference stages. Specifically, we utilize an LLM to learn the alignment between user queries and tool document representations, thereby generating high-quality user queries. Additionally, we employ a frozen retrieval model to compute the similarity between the queries and the tool database.

