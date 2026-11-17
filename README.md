# kirinuki-models

切り抜きツール（kirinuki）が使う文字起こしモデルの置き場。コードや個人のデータは置かない。ファイルは Releases に添付。

## whisper-large-v3-turbo

faster-whisper 用 Whisper large-v3-turbo を zip 1 つにまとめたもの。

- 出典：https://huggingface.co/mobiuslabsgmbh/faster-whisper-large-v3-turbo （MIT）
- 元モデル：OpenAI Whisper（MIT）

## 使い方

```
python -m kirinuki model large-v3-turbo --url <zip の URL> --sha256 <値>
```
