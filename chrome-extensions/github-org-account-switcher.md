# Privacy Policy — GitHub Org Account Switcher

_Last updated: 2026-07-01_

GitHub Org Account Switcher（以下「本拡張」）は、ユーザーのプライバシーを最優先に設計されています。
This extension is designed to be privacy-first.

## 日本語

### 収集するデータ
**ありません。** 本拡張は個人情報・閲覧履歴・認証情報を一切収集しません。

### Cookie / セッション
本拡張は Cookie やセッション情報を**読み取り・書き込み・改変・保存しません**。アカウントの切り替えは、GitHub が提供する標準のマルチアカウント切り替え UI を操作することでのみ行われます。

### 保存される情報
ユーザーが設定画面で入力した設定（アカウントと Org の対応、トリガーモード、デバッグフラグ、表示言語）のみを、ブラウザの `chrome.storage.sync` に保存します。この情報はユーザー自身のブラウザ、および同じ Google アカウントでサインインした Chrome 間でのみ同期され、開発者や第三者には送信されません。

### 外部送信 / トラッキング
本拡張は**一切の外部通信を行いません**。ネットワークリクエスト、アナリティクス、トラッキング、広告は含まれていません（100% ローカル動作）。

### 権限
- `webNavigation`: github.com 上での SPA ページ遷移を検知するためだけに使用します。
- `storage`: 上記のユーザー設定を保存するために使用します。
- `https://github.com/*`: github.com 上でのみ動作し、現在のアカウント検出と標準 UI の操作に使用します。

## English

### Data we collect
**None.** This extension does not collect any personal information, browsing history, or credentials.

### Cookies / sessions
This extension does **not** read, write, modify, or store cookies or session data. Account switching is performed solely by driving GitHub's own native multi-account switcher UI.

### Stored information
Only the settings you enter on the options page (account-to-Org mapping, trigger mode, debug flag, UI language) are stored, via the browser's `chrome.storage.sync`. This data is synced only across your own Chrome browsers signed in to the same Google account and is never transmitted to the developer or any third party.

### External transmission / tracking
This extension makes **no external network requests**. It contains no analytics, tracking, or advertising — it runs 100% locally.

### Permissions
- `webNavigation`: used only to detect SPA navigations on github.com.
- `storage`: used to save the user settings described above.
- `https://github.com/*`: operates only on github.com, to detect the current account and drive the native switcher UI.

## Contact
For questions about this policy, please open an issue in the source repository linked above.
