ดึงข้อมูล( "https://discord.com/api/v8/channels/ <channel_id> / เชิญ" , {
    ส่วนหัว : {
        "content-type" : "application / json" ,
        การอนุญาต : "Your_token"
    } ,
    ร่างกาย : JSON stringify ( {
        "max_age" : 3600 ,
        "max_uses" : 0 ,
        "target_application_id" : "755600276941176913" ,  // Youtube Together | 755827207812677713 โป๊กเกอร์ไนท์ | 773336526917861400 Betrayal.io | 814288819477020702 Fishington.io
        "target_type" : 2 ,
        "ชั่วคราว" : เท็จ
    } ) ,
    วิธีการ : "POST"
} ) . จากนั้น( ความละเอียด=> Res . JSON ( ) ) แล้ว( คอนโซล. ล็อก)
