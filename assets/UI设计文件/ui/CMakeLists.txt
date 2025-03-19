SET(SOURCES screens/ui_home.c
    screens/ui_settings.c
    screens/ui_playPage1.c
    screens/ui_playPage2.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    images/ui_img_1572002003.c
    images/ui_img_home_2v2_png.c
    images/ui_img_home_cpu_png.c
    images/ui_img_settings_png.c
    images/ui_img_814085921.c
    images/ui_img_1993502234.c
    images/ui_img_1452054505.c
    images/ui_img_49543422.c
    images/ui_img_1144387654.c
    images/ui_img_play_bg_png.c
    images/ui_img_back_png.c
    images/ui_img_loader_png.c
    images/ui_img_famer_png.c
    images/ui_img_vs_png.c
    images/ui_img_card_2_png.c
    images/ui_img_card_4_png.c
    images/ui_img_card_5_png.c
    images/ui_img_card_6_png.c
    images/ui_img_card_7_png.c
    images/ui_img_card_8_png.c
    images/ui_img_card_9_png.c
    images/ui_img_card_1_png.c
    images/ui_img_card_3_png.c)

add_library(ui ${SOURCES})
