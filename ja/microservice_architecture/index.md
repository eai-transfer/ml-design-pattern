# Microservice Architecture

## 概要

- 複雑なアプリケーション間でのやり取りを無くして、標準的なインターフェースで通信を行う

## Intent

データコネクション、データ変換、可視化などの機能を小さなサービスとして作成し、それぞれのサービスでの通信を統一する

## Problem

- アプリケーション間で通信することができる
- それぞれのサービスを別のアプリケーションに対して利用できる 

## Soluition

アプリケーション間のインターフェイスを同一フォーマットで行う

## Context

- フェーズ：システム全体のアーキテクチャ設計
- MLアプリケーションの利用環境：一般

## Discussion

複雑なアプリケーション間通信を管理する中間層が必要ないこと

