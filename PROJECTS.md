# ◇ これまでの案件（実績）一覧 ◇

# ■ レガシーシステムの技術刷新  
**Flex（ActionScript）＋Struts → React ＋ Spring Boot マイグレーション**

---

## ● 概要

既存業務システム（Flex＋Struts）をモダンな技術スタック（React＋Spring Boot）へ移行。  
既存構造を踏襲しつつ、保守性・拡張性を高めた設計で再構築を実施しました。

---

## ● プロジェクト概要

| 項目 | 内容 |
|------|------|
| **期間** | 2024年9月〜現在 |
| **目的** | レガシーシステムの技術刷新（Flex / Struts → React / Spring Boot） |
| **規模** | 22名（主任1名、副主任1名、SE兼PG9名、PG[FE]9名、PG[BE]2名） |
| **担当** | バックエンド（主担当）／フロントエンド（5月以降より補助） |
| **フェーズ** | 実装・単体テスト・実装手順書作成・ナレッジ共有・技術支援 |

---

## ● 担当業務

### 🔸 バックエンド（Struts → Spring Boot）
- 共通部品の設計思想を踏襲し、**Spring Boot + REST API** で再構築  
- **iBatis → MyBatis** への移行対応  
  - 正規表現を用いた変換パターン一覧を作成し、自動変換ツールを開発  
- **実装手順書の作成／ナレッジ共有推進**
  - フロントエンドエンジニア向けに、初心者でも理解しやすい手順書を整備  
  - 問い合わせの多い事項をドキュメント化し、再利用可能なナレッジとして展開  
- 他メンバーへの技術支援・質疑応答対応

### 🔸 フロントエンド（Flex → React）※5月以降担当
- **ActionScript (Flex + MXML + BlazeDS)** 実装を  
  **React + TypeScript + MUI + SWR** 構成でSPA化  
- BlazeDS通信をJSON形式のREST API通信に置き換え  
- **MUI**によるUI統一・再利用性の高い設計を意識して画面構築を実施  

---

## ● 工夫・成果

- 新技術導入に伴う**学習コストを低減**
  - 実装手順書・FAQ・自動変換ツールを整備し、チーム全体の生産性を向上  
- フロント／バックエンド間の仕様連携を明文化し、**横断的な支援体制を確立**  
- ナレッジ蓄積により、後続メンバーのオンボーディング効率を大幅改善  

---

## ● システム環境

### OS
- Windows 11

### フロントエンド
- Flex（ActionScript / MXML / BlazeDS）  
- React 18 / Next.js 14 / TypeScript 5  
- UI：MUI  
- 状態管理・通信：SWR 2  
- 静的解析：ESLint 8  
- テスト：Jest 29  
- Node.js：v20

### バックエンド
- Java（17, 21）  
- Spring Boot 3  
- MyBatis 3（iBatis から移行）  
- Lombok / Jackson 2 / Logback

### データベース
- Oracle SQL / Oracle DB

### 主なツール
- GitLab / TortoiseSVN  
- SQL Developer  
- IntelliJ IDEA / Visual Studio Code  
- サクラエディタ / IP Messenger / FFFTP  

---

## ● まとめ

> Struts＋Flexベースの既存システムを、Spring Boot＋React構成へモダン化。  
> iBatisからMyBatisへの移行自動化ツールを開発し、BE・FE両面から再構築を支援。  
> チーム全体の生産性向上・ナレッジ共有に貢献しました。

---

**Role:** Backend Engineer（Partial Frontend Support）  
**Tech Stack:** React / TypeScript / Spring Boot / MyBatis / OracleDB  
**Period:** 2024–2025  
**Team Size:** 22 members  
