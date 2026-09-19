# MingToon 0.1.11

Open Beta · BRP Core · Unity 2021.3 / 2022.3 LTS

## English

- **Edge Rim** is a new contour rim module, and lilToon's backlight moved to a separate module with a colour map, view wrap, directivity and a backface mask.
- Conversion now enables authored reflection toggles, cube maps and colour maps, carries a distance fade per extra-texture layer, and no longer lets look or colour presets overwrite the converted base tint, alpha, shadow operator or rim data.
- Depth-based effects are renamed to **Depth Shadow**, **Depth Rim Light** and **SSSSS (Experimental)**. Eight stored property IDs migrate automatically; only directly bound clips and FX layers need rebinding.
- A single **Environment Intensity** control scales world colour, indirect light, Light Volume and the finished shadow colour. Its default of 1 leaves existing looks unchanged.
- Factory looks ship with **Edge Rim** off and **Volume Specular** off, and all 18 looks were retuned against the studio's reference character.
- The first conversion no longer waits on a cyan placeholder. The installer prepares the full directional-light superset before the first conversion and keeps compiling the remaining lighting states in the background.
- Fixed VRChat upload optimization on deep project paths: generated-shader recovery no longer exceeds the Windows path limit, so candidate materials switch to the optimized profile instead of being skipped.
- The repeated shader recompile after the first conversion is fixed, and installing this version no longer triggers a reimport of the project's whole texture set.

Back up before updating. Restore previously baked materials to editable form, then re-bake and re-upload avatars to apply the changes. This package contains BRP Core; URP and Ming Light Controller are separate. Existing noncommercial Open Beta terms apply.

Known limitation: VRC Light Volume cast-shadow appearance in v2 and v3 worlds still differs from 0.1.10. Light Volumes 3 worlds use the legacy v2 buffer only; native v3 shadows, clustering and per-light shading are unsupported.

[Full patch notes](https://studioraming.github.io/mingtoon-docs/en/changelog/0.1.11#v0111) · [Install / update](https://studioraming.github.io/mingtoon-site/en/download/)

## 日本語

- 輪郭に沿う独立モジュール **エッジリム** を追加し、lilToonの逆光はカラーマップ・視点方向の巻き込み・逆光集中度・裏面マスクを持つ別モジュールへ移しました。
- 変換時に、作成済みの反射トグル・キューブマップ・反射カラーマップを有効にし、追加テクスチャレイヤーごとの距離フェードを引き継ぎます。ルックプリセットと色調プリセットが、変換後のベース色・アルファ・影方式・リムデータを上書きしなくなりました。
- 深度ベースの効果名を **デプスシャドウ**・**デプスリムライト**・**SSSSS（実験的）** に統一しました。保存済みプロパティ8個は自動移行し、直接バインドしたクリップとFXだけ再接続が必要です。
- **環境光の反映倍率** 1つで、ワールドの環境色・間接光・Light Volume・完了した影色をまとめて調整できます。既定値1では既存のルックは変わりません。
- ファクトリールックは **エッジリム** オフ・**ボリュームスペキュラー** オフで配布され、18個すべてをスタジオの基準キャラクターに合わせて再調整しました。
- 初回変換がシアンのプレースホルダーで止まらなくなりました。初回変換の前にディレクショナルライト用のインストールスーパーセットを準備し、残りのライティング状態はバックグラウンドでコンパイルを続けます。
- 深いプロジェクトパスで VRChat アップロード最適化が失敗していた問題を修正しました。生成シェーダーの復旧処理が Windows のパス長制限を超えなくなり、対象マテリアルがスキップされず最適化プロファイルへ切り替わります。
- 初回変換後に残っていたシェーダー再コンパイルを修正し、このバージョンのインストールでプロジェクト全体のテクスチャが再インポートされることもなくなりました。

更新前にバックアップしてください。ベイク済みマテリアルは編集用に復元して再ベイクし、アバターも再アップロードすると変更が反映されます。本パッケージはBRP Coreです。URPとMing Light Controllerは別製品で、既存の非商用Open Beta利用条件が適用されます。

既知の制限: v2・v3ワールドのVRC Light Volumeキャスト影は、0.1.10とまだ見え方が異なります。Light Volumes 3ワールドは旧v2バッファーのみを読み、v3ネイティブの影・クラスタリング・ライト別シェーディングには未対応です。

[詳しい変更点](https://studioraming.github.io/mingtoon-docs/ja/changelog/0.1.11#v0111) · [導入・更新](https://studioraming.github.io/mingtoon-site/ja/download/)

## 한국어

- 윤곽을 따라가는 별도 모듈 **엣지 림**을 추가하고, lilToon의 백라이트를 색상 맵·시점 감쌈·역광 집중도·뒷면 마스크를 가진 별도 모듈로 옮겼습니다.
- 변환 시 저작된 반사 토글·큐브맵·반사 색상 맵을 켜고, 추가 텍스처 레이어마다 거리 페이드를 함께 옮깁니다. 룩 프리셋과 색감 프리셋이 변환된 베이스 색·알파·그림자 연산 방식·림 데이터를 더 이상 덮어쓰지 않습니다.
- 깊이 기반 효과 이름을 **뎁스 그림자**·**뎁스 림라이트**·**SSSSS(실험적)**로 통일했습니다. 저장된 속성 8개는 자동으로 옮겨지고, 직접 바인딩한 클립과 FX만 다시 연결하면 됩니다.
- **환경광 반영 배수** 하나로 월드 환경 색·간접광·Light Volume·완료된 그림자 색을 한 번에 조절합니다. 기본값 1에서는 기존 룩이 바뀌지 않습니다.
- 팩토리 룩은 **엣지 림** 꺼짐·**볼륨 스페큘러** 꺼짐으로 배포되며, 18개 전부 스튜디오 기준 캐릭터에 맞춰 다시 조정했습니다.
- 첫 변환이 시안색 플레이스홀더에서 멈추지 않습니다. 첫 변환 전에 디렉셔널 라이트 설치 슈퍼셋을 준비하고, 나머지 라이팅 상태는 백그라운드에서 계속 컴파일합니다.
- 깊은 프로젝트 경로에서 VRChat 업로드 최적화가 실패하던 문제를 수정했습니다. 생성 셰이더 복구 임시 경로가 Windows 경로 길이 제한을 넘지 않아, 대상 재질이 건너뛰어지지 않고 최적화 프로파일로 전환됩니다.
- 첫 변환 후 남아 있던 셰이더 재컴파일을 수정했고, 이 버전을 설치해도 프로젝트 전체 텍스처가 다시 임포트되지 않습니다.

업데이트 전에 백업해 주세요. 기존 베이크 재질은 편집용으로 복원한 뒤 다시 베이크하고, 아바타도 재업로드해야 변경이 반영됩니다. BRP 코어 패키지이며 URP와 Ming Light Controller는 별도입니다. 기존 비상업용 Open Beta 이용 조건이 적용됩니다.

알려진 제한: v2·v3 월드의 VRC Light Volume 캐스트 그림자 룩은 0.1.10과 아직 다릅니다. Light Volumes 3 월드는 기존 v2 버퍼만 읽으며, v3 네이티브 그림자·클러스터링·라이트별 셰이딩은 지원하지 않습니다.

[전체 패치노트](https://studioraming.github.io/mingtoon-docs/changelog/0.1.11#v0111) · [설치·업데이트](https://studioraming.github.io/mingtoon-site/ko/download/)

---

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
