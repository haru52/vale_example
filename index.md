# Example Document

- This misspeling and passive voice will be detected by Vale
- Vale cannot fix errors and warnings automatically
- Vale allows fuga and hoge words in this project

<!-- Vale の全チェックを無効化する ignore コメント -->
<!-- vale off -->
This misspeling and passive voice won't be detected!
<!-- 再度有効化 -->
<!-- vale on -->

<!-- Vale の特定のルールのみを無効化する ignore コメント -->
<!-- vale Vale.Spelling = NO -->
This passive voice will be detected but not this misspeling!
<!-- vale Vale.Spelling = YES -->
