# 従業員台帳 プロジェクト設定



## テンプレート変数の展開値



| 変数 | 値 |

|---|---|

| `{{PROJECT_NAME}}` | 従業員台帳 |

| `{{CLIENT_NAME}}` | 株式会社KAKUZEN |

| `{{DB_STACK}}` | Supabase |

| `{{REPO_NAME}}` | employee-ledger |

| `{{GHPAGES_URL}}` | https://kiwamoto202602-a11y.github.io/employee-ledger |

| `{{FIREBASE_PROJECT_ID}}` | (Supabase使用のため該当なし) |

| `{{SUPABASE_PROJECT_REF}}` | (記入) |

| `{{MONTHLY_PLAN}}` | (記入) |



## プロジェクト固有情報



### 技術スタック

- **DB**: Supabase (Postgres)

- **認証**: Supabase Auth

- **ファイル保存**: Supabase Storage

- **公開**: GitHub Pages



### アプリ概要

株式会社KAKUZEN従業員管理のための従業員台帳アプリ。

個人情報・雇用契約・有給管理・資格証明書管理を含む。



## プロジェクト固有のルール・メモ



### 関連アプリ

- **KAKUZEN派遣管理アプリ** (`dispatch-kanri` リポジトリ)

&#x20; - 同じクライアント(株式会社KAKUZEN)で運用

&#x20; - ただしSupabaseプロジェクトはアプリ単位で完全分離



### データ取り扱い上の注意

- 従業員の個人情報を扱うため、RLS(Row Level Security)を厳密に設定

- 退職者データの取り扱いは別途クライアント確認



## 更新履歴



| 日付 | 内容 |

|---|---|

| 2026-04-23 | 新雛形CLAUDE.md適用、CLAUDE.local.md初版作成 |

