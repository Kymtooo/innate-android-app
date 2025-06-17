# 🌱 INNATE - 習慣を穏やかに育てるAndroidアプリ


     **内なる習慣を、穏やかに**
     

     ## ✨ 特徴

     - **🏠 ウィジェット中心設計**:
     ホーム画面から直接習慣を開始
     - **🔗 習慣チェーン**:
     習慣同士を連鎖させて効率的な継続をサポート
     - **🎯 マイクロリワード**: 小さな達成感で負担なく継続
     - **🔒 プライバシー重視**:
     すべてのデータはローカル保存、外部送信なし
     - **🌙 穏やかなUX**: 意志力を消費しないデザイン


     ## 🚀 インストール方法

     ### APKダウンロード（推奨）
     1. [最新リリース](https://github.com/Kymtooo/innate-android-app/releases)からAPKファイルをダウンロード
     2. Androidの「設定」→「セキュリティ」→「不明なソースか
     らのインストール」を許可
     3. APKファイルをタップしてインストール

     ### 動作要件
     - **Android 8.0** (API level 26) 以上
     - **RAM**: 4GB以上推奨
     - **ストレージ**: 50MB以上の空き容量

     ## 🔧 技術スタック

     ### フロントエンド
     - **Kotlin** - 100% Kotlin実装
     - **Jetpack Compose** - Modern UIツールキット
     - **Material Design 3** - 最新のデザインシステム

     ### アーキテクチャ
     - **MVVM** - Repository パターン
     - **Hilt** - 依存性注入
     - **Room** - ローカルデータベース（migration対応）
     - **DataStore** - 設定データ管理

     ### 機能実装
     - **Glance App Widgets** - ホーム画面ウィジェット
     - **WorkManager** - バックグラウンド処理
     - **Foreground Services** - セッション継続
     - **StateFlow + Coroutines** - 非同期処理・状態管理

     ## 🏗️ プロジェクト構造

     ```
     app/src/main/java/com/innateapp/innate/
     ├── data/
     │   ├── local/          # Room database, DAO
     │   ├── model/          # データモデル
     │   └── repository/     # Repository実装
     ├── domain/             # ビジネスロジック
     ├── ui/
     │   ├── components/     # 再利用可能なUIコンポーネント
     │   ├── screens/        # 各画面のComposable
     │   └── theme/          # Material Design 3テーマ
     ├── widget/             # Glance ウィジェット
     ├── services/           # Foreground Services
     └── workers/            # WorkManager background tasks
     ```

     ## 🎯 主要機能

     ### 習慣管理
     - **アンカー設定**:
     時間ベース、アクションベース、習慣ベースのトリガー
     - **ペース設定**: 毎日、平日、週末、カスタム曜日
     - **ステップ分割**: 大きな習慣を小さなアクションに分割

     ### セッション管理
     - **リアルタイム進捗**: StateFlowによる状態同期
     - **中断・再開**: フォアグラウンドサービスで継続性確保
     - **マイクロリワード**: 各ステップ完了時の達成感

     ### データ管理
     - **ローカル完結**: 外部サーバーへのデータ送信なし
     - **自動バックアップ**: JSON形式でのエクスポート機能
     - **カスタム日付境界**: ユーザー定義の1日開始時刻

     ## 🛠️ 開発環境構築

     ### 必要なツール
     - **Android Studio** Hedgehog 2023.1.1 以上
     - **JDK** 17 以上
     - **Gradle** 8.2 以上

     ### セットアップ
     ```bash
     git clone
     https://github.com/[your-username]/[your-repo].git
     cd INNATE
     ./gradlew build
     ```

     ### ビルド
     ```bash
     # Debug APK
     ./gradlew assembleDebug

     # Release AAB (署名が必要)
     ./gradlew bundleRelease
     ```

     ## 🧪 テスト

     ```bash
     # Unit Tests
     ./gradlew testDebugUnitTest

     # Instrumented Tests
     ./gradlew connectedAndroidTest
     ```

     ## 📊 アプリサイズ最適化

     - **元サイズ**: 31.10MB
     - **最適化後**: 9.99MB (68%削減)
     - **ProGuard/R8**: コード難読化・最適化
     - **リソース最適化**: 未使用リソース除去

     ## 🎨 デザイン

     ### カラーパレット
     - **プライマリ**: `#6366F1` (Indigo)
     - **セカンダリ**: `#10B981` (Emerald)
     - **背景**: `#0F172A` (Dark Slate)
     - **テキスト**: `#E2E8F0` (Light Gray)

     ### コンセプト
     「穏やかな継続」をテーマに、意志力を消費しないUI/UXを重
     視。

     ## 🔒 プライバシー

     - ✅ **すべてのデータはローカル保存**
     - ✅ **外部サーバーへの送信なし**
     - ✅ **トラッキングなし**
     - ✅ **広告なし**

     詳細: [プライバシーポリシー](https://Kymtooo.gi
     thub.io/innate-android-app/)


     ## 📧 連絡先

     - **Email**: innate.app.dev@gmail.com


     ---

     <div align="center">

     **⭐
     このプロジェクトが役に立ったらスターをお願いします！**

     Made with ❤️ by INNATE Development

     </div>
