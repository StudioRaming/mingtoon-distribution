# MingToon 0.1.10

Open Beta · BRP Core · Unity 2021.3 / 2022.3 LTS

## English

- Reduced repeated shader calculations and simplified outline lighting; improved bake reuse and recovery.
- Unified the Inspector layout, preset controls and compact performance indicators.
- Added clearer texture cards, section grouping and size sorting, plus bulk resolution and compression settings.
- Improved individual layer addition, enable/disable, movement and deletion, including checks for related animation curves.
- Added the default Plane face proxy and moved Receiver Pushback to Face Shading. With 2D Shadow enabled and pushback above zero, projected-shadow reception is disabled; switching 2D Shadow off or restoring zero restores the original setting.
- Improved lilToon conversion, color-only layers, depth-light and WARUDO build handling, and refreshed factory presets.

Back up before updating. Restore previously baked materials to editable form, then re-bake and re-upload to apply the changes. This package contains BRP Core; URP and Ming Light Controller are separate. Existing noncommercial Open Beta terms apply.

[Full patch notes](https://studioraming.github.io/mingtoon-docs/en/changelog/0.1.10#v0110) · [Install / update](https://studioraming.github.io/mingtoon-site/en/download/)

## 日本語

- シェーダーの重複計算とアウトラインの照明処理を軽量化し、ベイク結果の再利用と復元を改善しました。
- 設定画面、プリセット操作、コンパクトな負荷表示を統一しました。
- テクスチャカード、セクション別表示と容量順の並び替え、解像度・圧縮の一括設定を改善しました。
- レイヤーごとの追加・有効／無効・移動・削除を改善し、関連するアニメーションカーブも確認します。
- 顔プロキシに標準の平面モードを追加し、受信面の押し戻しを顔シェーディングに移しました。2Dシャドウが有効で押し戻しが0より大きい間は投影シャドウの受信を無効にし、2Dシャドウを切るか0に戻すと元の設定に戻ります。
- lilToon変換、色のみのレイヤー、深度ライト、WARUDOビルド処理を改善し、ファクトリープリセットを更新しました。

更新前にバックアップしてください。ベイク済みマテリアルは編集用に戻して再ベイクし、アバターも再アップロードすると変更が反映されます。本パッケージはBRP Coreです。URPとMing Light Controllerは別製品で、既存の非商用Open Beta利用条件が適用されます。

[詳しい変更点](https://studioraming.github.io/mingtoon-docs/ja/changelog/0.1.10#v0110) · [導入・更新](https://studioraming.github.io/mingtoon-site/ja/download/)

## 한국어

- 셰이더의 반복 계산과 아웃라인 조명 처리를 줄이고 베이크 재사용·복구를 개선했습니다.
- 인스펙터 배치, 프리셋 조작과 간결한 성능 부하 표시를 통일했습니다.
- 텍스처 카드, 섹션 묶기·용량순 정렬, 해상도·압축 일괄 설정을 개선했습니다.
- 레이어별 추가·켜기/끄기·이동·삭제와 관련 애니메이션 커브 확인을 개선했습니다.
- 기본 평면 얼굴 프록시를 추가하고 수신면 밀기를 얼굴 셰이딩으로 옮겼습니다. 2D 그림자가 켜져 있고 밀기가 양수이면 투영 그림자 수신이 꺼지며, 2D 그림자를 끄거나 밀기를0으로 돌리면 원래 설정으로 돌아옵니다.
- lilToon 변환, 색상 전용 레이어, 깊이 라이트·WARUDO 빌드 처리를 개선하고 팩토리 프리셋을 갱신했습니다.

업데이트 전에 백업해 주세요. 기존 베이크 재질은 편집용으로 복원한 뒤 다시 베이크하고, 아바타도 재업로드해야 변경이 적용됩니다. BRP 코어 패키지이며 URP와 Ming Light Controller는 별도입니다. 기존 비상업용 Open Beta 이용 조건이 적용됩니다.

[전체 패치노트](https://studioraming.github.io/mingtoon-docs/changelog/0.1.10#v0110) · [설치·업데이트](https://studioraming.github.io/mingtoon-site/ko/download/)

---

# MingToon 0.1.9

Open Beta / オープンベータ / 오픈 베타

## English

Improved Emission and Glitter appearance and lilToon shadow conversion. The Manager now has Get Started, Look & Bake and Optimize tabs, separate Look and Color Palette controls, reapply and Undo for existing MingToon materials, per-material conversion and texture-size limits.

[Full patch notes](https://studioraming.github.io/mingtoon-docs/en/changelog/0.1.9#v019)

## 日本語

Emission・Glitterの表現とlilToonの影変換を改善しました。Managerをはじめに・外観／ベイク・最適化の3タブに整理し、LookとColor Paletteの個別選択、既存MingToonマテリアルへの再適用とUndo、マテリアル単位の変換、テクスチャサイズ制限を追加しました。

[変更履歴](https://studioraming.github.io/mingtoon-docs/ja/changelog/0.1.9#v019)

## 한국어

Emission·Glitter 표현과 lilToon 그림자 변환을 개선했습니다. Manager를 시작하기 / 룩·베이크 / 최적화의 세 탭으로 정리하고, Look과 Color Palette 선택, 기존 MingToon 머티리얼 재적용과 Undo, 재질별 변환 및 텍스처 크기 제한을 추가했습니다.

[전체 패치노트](https://studioraming.github.io/mingtoon-docs/changelog/0.1.9#v019)

---

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
