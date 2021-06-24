from datetime import datetime

def sample_responses(input_text):
    user_message = str(input_text).lower()


    if user_message in ("哈囉","嗨"):
        return "請問有什麼需要幫忙的嗎？"

    if user_message in ("有選單嗎","你們有什麼功能","可以玩遊戲嗎？","你是誰"):
        return "您好！我是遊戲助理，這裡推薦您玩一款主編特別設計的遊戲，想玩玩看嗎？"

    if user_message in ("不了","不要","不想","不"):
        return "好吧，那我們只好請您上Google 搜索您想玩的遊戲"

    if user_message in ("好","來吧","我要玩","開始","好呀"):
        return "那我們這款遊戲叫做貪吃蛇，以下是他的連結"

    if user_message in ("time","time?",):
        now = datetime.now()
        date_time = now.strftime("%d/%m/%y,%H:%M:%S")

        return str(date_time)


    return "I have no idea what do u mean."
