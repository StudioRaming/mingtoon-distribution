# MingToon 0.1.8

Open Beta / オープンベータ / 오픈 베타

## English

- Preserved Unity-generated package manifest metadata during verified updates.

- The DLL installer downloads the release from the server and verifies it before replacing a recognized older MingToon installation. Existing materials and scenes are preserved.
- The update controls use a compact two-line layout, and the patch-notes button opens MingToon Docs.
- DLL installations show the current version, latest checked version, patch notes, and update controls in the MingToon Manager summary.
- Automatic updates are enabled by default when the Editor starts. Turn them off in MingToon Manager if preferred. VCC installations continue to use VCC for updates.
- Fixed installer startup and package resolution waiting while Unity is in the background, and delayed installation verification until compilation finishes.
- Identical shader bake requests are grouped to reduce repeated work during avatar preparation.
- Unity 2021.3 / 2022.3. BRP Core package; URP is a separate add-on. Existing open-beta terms and support limits apply: https://studioraming.github.io/mingtoon-site/en/download/

## 日本語

- 検証済み更新時にUnityが生成したパッケージマニフェストのメタデータを保持します。

- DLLインストーラーはサーバーからリリースを取得し、検証後に対応する旧MingToonを置き換えます。既存のマテリアルとシーンは保持されます。
- 更新操作をコンパクトな2行にまとめ、パッチノートのボタンからMingToon Docsを開くようにしました。
- DLLで導入した場合、MingToon Managerの概要に現在のバージョン、確認済みの最新バージョン、パッチノート、更新操作が表示されます。
- エディター起動時の自動更新は標準で有効です。MingToon Managerで無効にできます。VCCで導入した場合は、引き続きVCCで更新してください。
- Unityがバックグラウンドにあるとインストーラーの起動やパッケージ認識が待機する問題を修正しました。導入結果の確認はコンパイル完了後に行います。
- アバター準備中の重複処理を減らすため、同一のシェーダーベイク要求をまとめます。
- Unity 2021.3 / 2022.3対応。BRP Coreパッケージで、URPは別アドオンです。既存のオープンベータ利用条件と対応範囲が適用されます: https://studioraming.github.io/mingtoon-site/ja/download/

## 한국어

- 업데이트 검증 시 Unity가 생성한 패키지 매니페스트 메타데이터를 보존합니다。

- DLL 설치기가 서버에서 릴리스를 내려받아 검증한 뒤, 지원되는 기존 MingToon을 교체합니다. 기존 머티리얼과 씬은 보존합니다.
- 업데이트 영역을 작은 두 줄 UI로 줄이고 패치노트 버튼을 MingToon Docs에 연결했습니다.
- DLL로 설치하면 MingToon Manager 요약에 현재 버전, 확인한 최신 버전, 패치노트, 업데이트 조작이 표시됩니다.
- 에디터 시작 시 자동 업데이트는 기본으로 켜져 있으며 MingToon Manager에서 끌 수 있습니다. VCC로 설치한 경우에는 계속 VCC에서 업데이트합니다.
- Unity가 백그라운드에 있을 때 설치 창 열기와 패키지 인식이 대기하던 문제를 수정하고, 컴파일이 끝난 뒤 설치 결과를 확인하도록 변경했습니다.
- 아바타 준비 중 같은 셰이더 베이크 요청을 묶어 반복 작업을 줄입니다.
- Unity 2021.3 / 2022.3 지원. BRP Core 패키지이며 URP는 별도 애드온입니다. 기존 오픈 베타 이용 조건과 지원 제한이 적용됩니다: https://studioraming.github.io/mingtoon-site/ko/download/
