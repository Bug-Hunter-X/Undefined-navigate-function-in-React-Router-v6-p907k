# React Router v6 navigate function undefined

This repository demonstrates a common error encountered when using the `useNavigate` hook in React Router v6 within a functional component. The error occurs when attempting to use the `navigate` function without properly importing and using it. 

## Problem

The `navigate` function is not available within the `Home` component, resulting in a runtime error. This is because  `useNavigate` hook needs to be imported and used correctly.

## Solution

The solution involves importing the `useNavigate` hook from `react-router-dom` and using it correctly within the functional component.