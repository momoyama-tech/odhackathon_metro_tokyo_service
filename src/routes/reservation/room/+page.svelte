<main>
    <header class="header">
        <h1>トイレ予約 TOTO 予約フォーム</h1>
    </header>

    <form id="reservationForm">
        <label for="name">お名前:</label>
        <input type="text" id="name" name="name" required>

        <label for="age">年齢:</label>
        <input type="text" id="age" name="age" required>

        <label for="phone">電話番号:</label>
        <input type="tel" id="phone" name="phone" required>

        <button type="submit">予約する</button>
    </form>

    <h1>ルーム予約</h1>
    <a href="/reservation/result">予約する</a>
</main>


<style>
	/* ヘッダーに赤い背景色を適用するスタイル */
    .header {
        background-color: red; /* 赤い背景色 */
        color: white;          /* テキストの色を白に設定 */
        padding: 10px;        /* パディングでスペースを確保 */
        margin: 0;            /* マージンをゼロに設定 */
        text-align: center;   /* テキストを中央に配置 */
    }
</style>