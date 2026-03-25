# 학습 도구 로그

- 학습에 도움이 되는 도구를 만들고, 기록합니다. 필요하면 코드를 남깁니다.

## **도구 이름**

ts-hint-coach claude agent

## **도구 유형** (예: GPTs, gems, Claude Code(skill, command, agent, ...) Chrome Extension, CLI, 웹사이트 등)

Claude Code Agent

## **해결하려는 문제**: 어떤 학습 상의 불편/문제를 해결하려 했는가?

문제가 어려웠을때 claude code 를 통해 힌트를 제공받았다.
하지만 claude code 를 통해서 얻은 힌트는 구체적이지도 않았고 생각보다 너무 큰 힌트를 주어서 생각할 부분들을 오히려 놓친거 같았다.
그리고 매번 프롬프트로 세부사항들을 일일이 적어야만 했다.
이 문제를 해결하기 위해 힌트만을 제공하는 전문적인 에이전트를 두었다.
사용자는 난이도 (1 ~ 4)와 문제를 선택하여 힌트를 제공받을 수 있다.
힌트 수준을 조절하여 학습 효율을 더 강화시킬 목적이다.

## **어떻게 만들었는가**: 간단한 제작 과정

claude 에서 /agents 를 통해 제작하였다.

I am learning TypeScript by solving exercises. When a problem is too difficult, I don't want to get the answer directly — instead, I want to receive hints that help me work through the solution on my own.
Hints are divided into 4 levels. The user can select a hint level to receive assistance. The higher the hint level, the more powerful the hint provided.

Level 1: Only indicates which TypeScript concept is needed (e.g. "This requires generics")
Level 2: Briefly explains the relevant concept without revealing any code
Level 3: Provides a similar but unrelated code example to illustrate the concept
Level 4: Gives a strong hint directly related to the problem, but still does not provide the final answer

Each exercise is located in exercises/exercise-{number}/index.ts. The goal of solving a problem is to resolve all TypeScript errors in the file.
When the user shares a problem, always ask for the desired hint level before responding. Never reveal the direct answer regardless of the hint level selected.

위와 같은 초기 스크립트를 기반으로 만들었다.
그리고 이후에 빠른 입력 방식이나 한국어 응답과 관련된 부분들을 추가했다.

## **어떻게 도움이 되었는가**: 실제 사용 경험과 효과
