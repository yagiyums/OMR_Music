# OMR_Music
This is a Program what to play "OnlyMyRailgun"

/*********************************/
/*   Music Program for Arduino   */
/*********************************/

#define PIN 9 //出力ピン


/***********************************
    *音符長(QuarterNote = 80M.M.)*
************************************/
#define Ful 3000 //全音符(Full Note)
#define Hal 1500 //2分音符(Half Note)
#define Quat 750 //4分音符(Quarter Note)
#define Quav 375 //8分音符(Quaver Note)
#define SQuav 188 //16分音符(SemiQuaver Note)
#define DSQuav 64 //32分音符(DemiSemiQuaver Note)
#define QQuav 32 //64分音符(64th Note)


/**************
     *音階*
***************/
#define zDa 131 //"-ド"
#define zLe 147 //"-レ"
#define zMi 165 //"-ミ"
#define zFa 175 //"-ファ"
#define zSo 196 //"-ソ"
#define zLa 220 //"-ラ"
#define zSi 247 //"-シ"

#define aDa 262 //"ド"
#define aLe 294 //"レ"
#define aMi 330 //"ミ"
#define aFa 349 //"ファ"
#define aSo 392 //"ソ"
#define aLa 440 //"ラ"
#define aSi 494 //"シ"

#define bDa 523 //"ド'"
#define bLe 587 //"レ'"
#define bMi 659 //"ミ'"
#define bFa 698 //"ファ'"
#define bSo 784 //"ソ'"


void setup(){
}

void loop(){
  //伴奏
  delay(Quat);
  //1st bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  
  //2nd bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  
  //3rd bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  
  //4th bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  
  //5th bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  
  //6th bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  
  //7th bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  
  //8th bar
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  tone(PIN,zFa,DSQuav);
  delay(DSQuav);
  //delay(QQuav);
  tone(PIN,zSo,SQuav);
  delay(SQuav);
  delay(DSQuav);
  //歌い出し
  tone(PIN,aSi,SQuav);//は
  delay(SQuav);
  tone(PIN,aLa,SQuav);//な
  delay(SQuav);
  tone(PIN,aFa,SQuav);//て
  delay(SQuav);
  delay(QQuav);
  
  //9th bar
  tone(PIN,aFa,SQuav);//こ
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//こ
  delay(DSQuav);
  tone(PIN,aSo,Quav);//ろ
  delay(Quav);
  tone(PIN,aFa,SQuav);//に
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//き
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//ざ
  delay(DSQuav);
  tone(PIN,aSo,Quav);//ん
  delay(Quav);
  tone(PIN,aFa,SQuav);//だ
  delay(SQuav);
  delay(QQuav);
  
  //10th bar
  tone(PIN,aFa,SQuav);//ゆ
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//め
  delay(DSQuav);
  tone(PIN,aSo,Quav);//も
  delay(Quav);
  delay(QQuav);
  tone(PIN,aSo,SQuav);//み
  delay(SQuav);
  tone(PIN,aSo,SQuav);//ら
  delay(SQuav);
  tone(PIN,aLa,SQuav);//い
  delay(SQuav);
  tone(PIN,aSi,SQuav);//さ
  delay(SQuav);
  tone(PIN,bDa,SQuav);//え
  delay(SQuav);
  
  //11th bar
  tone(PIN,aLa,Quav);//お
  delay(Quav);
  tone(PIN,aFa,Quav);//き
  delay(Quav);
  tone(PIN,bMi,Quav);//ざ
  delay(Quav);
  tone(PIN,bDa,Quav);//り
  delay(Quav);
  
  //12th bar
  tone(PIN,bDa,Quav);//に
  delay(Quav);
  tone(PIN,bDa,SQuav);//し
  delay(SQuav);
  tone(PIN,bLe,SQuav);//て
  delay(Quav);
  
  tone(PIN,aSi,SQuav);//げ
  delay(SQuav);
  tone(PIN,aLa,SQuav);//ん
  delay(SQuav);
  tone(PIN,aFa,SQuav);//か
  delay(SQuav);
  delay(QQuav);
  
  //13th bar
  tone(PIN,aFa,SQuav);//い
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//な
  delay(DSQuav);
  tone(PIN,aSo,Quav);//ど
  delay(Quav);
  tone(PIN,aFa,SQuav);//し
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//ら
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//な
  delay(DSQuav);
  tone(PIN,aSo,Quav);//い
  delay(Quav);
  tone(PIN,aFa,SQuav);//い
  delay(SQuav);
  delay(QQuav);
  
  //14th bar
  tone(PIN,aFa,SQuav);//み
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//な
  delay(DSQuav);
  tone(PIN,aSo,Quav);//い
  delay(Quav);
  delay(QQuav);
  tone(PIN,aSo,SQuav);//こ
  delay(SQuav);
  tone(PIN,aSo,SQuav);//の
  delay(SQuav);
  tone(PIN,aLa,SQuav);//ち
  delay(SQuav);
  tone(PIN,aSi,SQuav);//か
  delay(SQuav);
  tone(PIN,bDa,SQuav);//ら
  delay(SQuav);
  
  //15th bar
  tone(PIN,aSo,Quat);//が
  delay(Quat);
  delay(DSQuav);
  
  tone(PIN,aSo,SQuav);//ひ
  delay(SQuav);
  tone(PIN,aLa,SQuav);//か
  delay(SQuav);
  tone(PIN,aSi,SQuav);//り
  delay(SQuav);
  tone(PIN,bDa,SQuav);//ち
  delay(SQuav);
  
  //16th bar
  tone(PIN,aLa,Quav);//ら
  delay(Quav);
  tone(PIN,aFa,Quav);//す
  delay(Quav);
  tone(PIN,aLe,Quav);//そ
  delay(Quav);
  tone(PIN,aFa,Quav);//の
  delay(Quav);
  delay(QQuav);
  
  //17th bar
  tone(PIN,aFa,SQuav);//さ
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//き
  delay(DSQuav);
  tone(PIN,aSo,Quav);//に
  delay(Quav);
  //delay(QQuav);
  tone(PIN,aSi,SQuav);//は
  delay(SQuav);
  tone(PIN,aLa,SQuav);//る
  delay(SQuav);
  tone(PIN,aFa,DSQuav);//か
  delay(DSQuav);
  tone(PIN,aLe,Quav);//な
  delay(Quav);
  //delay(QQuav);
  tone(PIN,aFa,SQuav);//お
  delay(SQuav);
  
  //18th bar
  tone(PIN,aFa,SQuav);//も
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//い
  delay(DSQuav);
  tone(PIN,aSo,Hal);//を
  delay(Hal);
  delay(Quat);
  
  //19th bar
  //ここまで
  
  //20th bar
  tone(PIN,aLa,Quat);//あ
  delay(Quat);
  tone(PIN,aLa,SQuav);//る
  delay(SQuav);
  tone(PIN,aSo,SQuav);//い
  delay(SQuav);
  tone(PIN,aLa,SQuav);//て
  delay(SQuav);
  tone(PIN,aSi,SQuav);//き
  delay(SQuav);
  
  //21th bar
  tone(PIN,aLa,Quat);//た
  delay(Quat);
  tone(PIN,aLa,SQuav);//こ
  delay(SQuav);
  tone(PIN,aSo,SQuav);//の
  delay(SQuav);
  tone(PIN,aLa,SQuav);//み
  delay(SQuav);
  tone(PIN,aSi,SQuav);//ち
  delay(SQuav);
  
  //22th bar
  tone(PIN,bDa,Quat);//を
  delay(Quat);
  
  tone(PIN,bDa,SQuav);//ふ
  delay(SQuav);
  tone(PIN,bLe,SQuav);//り
  delay(SQuav);
  tone(PIN,bDa,SQuav);//か
  delay(SQuav);
  tone(PIN,aSi,SQuav);//え
  delay(SQuav);
  
  //23th bar
  tone(PIN,bDa,SQuav);//る
  delay(SQuav);
  tone(PIN,aSi,SQuav);//こ
  delay(SQuav);
  tone(PIN,aLa,SQuav);//と
  delay(SQuav);
  tone(PIN,bMi,SQuav);//し
  delay(SQuav);
  tone(PIN,bDa,Quat);//か
  delay(Quat);
  delay(QQuav);
  
  //24th bar
  tone(PIN,aLa,Quat);//で
  delay(Quat);
  tone(PIN,aLa,SQuav);//き
  delay(SQuav);
  tone(PIN,aSo,SQuav);//な
  delay(SQuav);
  tone(PIN,aLa,SQuav);//い
  delay(SQuav);
  tone(PIN,aSi,SQuav);//な
  delay(SQuav);
  
  //25th bar
  tone(PIN,aLa,Quat);//ら
  delay(Quat);
  delay(QQuav);
  tone(PIN,aLa,SQuav);//い
  delay(SQuav);
  tone(PIN,aSo,SQuav);//ま
  delay(SQuav);
  tone(PIN,aLa,SQuav);//こ
  delay(SQuav);
  tone(PIN,aSi,SQuav);//こ
  delay(SQuav);
  
  //26th bar
  tone(PIN,bDa,Quav);//で
  delay(Quav);
  delay(QQuav);
  tone(PIN,aFa,Quav);//す
  delay(Quav);
  tone(PIN,aSi,SQuav);//べ
  delay(SQuav);
  tone(PIN,aLa,SQuav);//て
  delay(SQuav);
  tone(PIN,aSo,SQuav);//を
  delay(SQuav);
  tone(PIN,aLa,SQuav);//こ
  delay(SQuav);
  
  //27th bar
  tone(PIN,aSo,Quav);//わ
  delay(Quav);
  tone(PIN,aSo,SQuav);//ー
  delay(SQuav);
  tone(PIN,aFa,SQuav);//せ
  delay(SQuav);
  tone(PIN,aFa,Quat);//る
  delay(Quat);
  
  //28th bar
  tone(PIN,bDa,SQuav);//く
  delay(SQuav);
  tone(PIN,bDa,DSQuav);//ら
  delay(DSQuav);
  tone(PIN,bDa,Quav);//や
  delay(Quav);
  tone(PIN,bDa,DSQuav);//み
  delay(DSQuav);
  tone(PIN,bDa,Quav);//に
  delay(Quav);
  delay(DSQuav);
  tone(PIN,bDa,SQuav);//お
  delay(SQuav);
  tone(PIN,aSi,SQuav);//ち
  delay(SQuav);
  tone(PIN,aLa,SQuav);//る
  delay(SQuav);
  delay(QQuav);
  
  //29th bar
  tone(PIN,aSo,Quav);//ま
  delay(Quav);
  tone(PIN,aSo,SQuav);//ち
  delay(SQuav);
  tone(PIN,bMi,SQuav);//な
  delay(SQuav);
  tone(PIN,bMi,Quat);//み
  delay(Quat);
  delay(QQuav);
  tone(PIN,bMi,SQuav);//ひ
  delay(SQuav);
  tone(PIN,bMi,SQuav);//と
  delay(SQuav);
  
  //30th bar
  tone(PIN,bMi,SQuav);//は
  delay(SQuav);
  tone(PIN,bLe,SQuav);//ど
  delay(SQuav);
  tone(PIN,bDa,SQuav);//こ
  delay(SQuav);
  tone(PIN,aSi,SQuav);//ま
  delay(SQuav);
  tone(PIN,bLe,DSQuav);//で
  delay(DSQuav);
  delay(QQuav);
  tone(PIN,bDa,SQuav);//た
  delay(SQuav);
  tone(PIN,aSi,Quav);//ち
  delay(Quav);
  tone(PIN,aLa,SQuav);//む
  delay(SQuav);
  
  //31th bar
  tone(PIN,aSo,SQuav+DSQuav);//か
  delay(SQuav+DSQuav);
  tone(PIN,aSo,Quav);//え
  delay(Quav);
  tone(PIN,aFa,SQuav);//る
  delay(SQuav);
  tone(PIN,aLa,Quat);//の
  delay(Quat);
  
  //32th bar
  tone(PIN,aLa,SQuav);//か
  delay(SQuav);
  tone(PIN,aLa,DSQuav);//そ
  delay(DSQuav);
  tone(PIN,aLa,Quav);//く
  delay(Quav);
  tone(PIN,aLa,DSQuav);//す
  delay(DSQuav);
  tone(PIN,aLa,Quav);//る
  delay(Quav);
  tone(PIN,aLa,SQuav);//そ
  delay(SQuav);
  tone(PIN,aSi,SQuav);//の
  delay(SQuav);
  tone(PIN,bDa,SQuav);//い
  delay(SQuav);
  
  //33th bar
  tone(PIN,aSi,Quav);//た
  delay(Quav);
  tone(PIN,aSi,SQuav);//み
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//か
  delay(DSQuav);
  tone(PIN,aSo,Quat);//ら
  delay(Quat);
  delay(QQuav);
  
  tone(PIN,aSo,SQuav);//だ
  delay(SQuav);
  
  //34th bar
  tone(PIN,aFa,Quav);//れ
  delay(Quav);
  tone(PIN,aFa,SQuav);//か
  delay(SQuav);
  tone(PIN,aMi,SQuav);//を
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//き
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//っ
  delay(DSQuav);
  tone(PIN,aLa,Quav);//と
  delay(Quav);
  delay(QQuav);
  tone(PIN,aLa,SQuav);//ま
  delay(SQuav);
  
  //35th bar
  tone(PIN,aLa,Quav+SQuav);//も
  delay(Quav+SQuav);
  delay(QQuav);
  tone(PIN,aSo,DSQuav);//れ
  delay(DSQuav);
  delay(QQuav);
  tone(PIN,aFa,DSQuav);//る
  delay(DSQuav);
  delay(QQuav);
  tone(PIN,aSo,Quat);//よ
  delay(Quat);
  delay(DSQuav);
  
  //36th bar
  tone(PIN,bMi,SQuav);//!
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,bFa,SQuav);//!!
  delay(SQuav);
  delay(DSQuav);
  tone(PIN,bMi,SQuav);//!!!
  delay(SQuav);
  delay(SQuav);
  
  tone(PIN,aSi,SQuav);//Loo!
  delay(SQuav);
  tone(PIN,aLa,SQuav);//king!
  delay(SQuav);
  tone(PIN,aFa,SQuav);//The
  delay(SQuav);
  delay(QQuav);
  
  //37th bar
  tone(PIN,aFa,SQuav);//bli
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//tz
  delay(DSQuav);
  tone(PIN,aSo,Quav);//loo
  delay(Quav);
  tone(PIN,aFa,SQuav);//p
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//pla
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//net
  delay(DSQuav);
  
  //38th bar
  tone(PIN,aSo,Quav);//to
  delay(Quav);
  
  tone(PIN,aFa,SQuav);//sea
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//ch
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//way.
  delay(DSQuav);
  tone(PIN,aSo,Quav);//On
  delay(Quav);
  delay(QQuav);
  tone(PIN,aSo,SQuav);//ly
  delay(SQuav);
  tone(PIN,aSo,SQuav);//My
  delay(SQuav);
  tone(PIN,aLa,SQuav);//RAIL
  delay(SQuav);
  tone(PIN,aSi,SQuav);//GUN
  delay(SQuav);
  
  //39th bar
  tone(PIN,bDa,SQuav);//can
  delay(SQuav);
  tone(PIN,aLa,Quav);//sho
  delay(Quav);
  tone(PIN,aFa,Quav);//ot
  delay(Quav);
  tone(PIN,bMi,Quav);//it.
  delay(Quav);
  
  //40th bar
  tone(PIN,bDa,Quav);//い
  delay(Quav);
  tone(PIN,bDa,Quav);//ま
  delay(Quav);
  tone(PIN,bDa,SQuav);//す
  delay(SQuav);
  tone(PIN,bLe,SQuav);//ぐ
  delay(Quav);
  
  tone(PIN,aSi,SQuav);//か
  delay(SQuav);
  tone(PIN,aLa,SQuav);//ら
  delay(SQuav);
  tone(PIN,aFa,SQuav);//だ
  delay(SQuav);
  delay(QQuav);
  
  //41th bar
  tone(PIN,aFa,SQuav);//じゅ
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//う
  delay(DSQuav);
  tone(PIN,aSo,Quav);//を
  delay(Quav);
  tone(PIN,aFa,SQuav);//ひ
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//か
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//り
  delay(DSQuav);
  tone(PIN,aSo,Quav);//の
  delay(Quav);
  tone(PIN,aFa,SQuav);//は
  delay(SQuav);
  delay(QQuav);
  
  //42th bar
  tone(PIN,aFa,SQuav);//や
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//さ
  delay(DSQuav);
  tone(PIN,aSo,Quav);//で
  delay(Quav);
  delay(QQuav);
  tone(PIN,aSo,SQuav);//か
  delay(SQuav);
  tone(PIN,aSo,SQuav);//け
  delay(SQuav);
  tone(PIN,aLa,SQuav);//め
  delay(SQuav);
  tone(PIN,aSi,SQuav);//ぐ
  delay(SQuav);
  tone(PIN,bDa,SQuav);//っ
  delay(SQuav);
  
  //43th bar
  tone(PIN,aSo,Quat);//た
  delay(Quat);
  delay(DSQuav);
  
  tone(PIN,aSo,SQuav);//た
  delay(SQuav);
  tone(PIN,aLa,SQuav);//し
  delay(SQuav);
  tone(PIN,aSi,SQuav);//か
  delay(SQuav);
  tone(PIN,bDa,SQuav);//な
  delay(SQuav);
  
  //44th bar
  tone(PIN,aLa,Quav);//よ
  delay(Quav);
  delay(DSQuav);
  tone(PIN,aFa,SQuav+DSQuav);//か
  delay(SQuav+DSQuav);
  delay(QQuav);
  tone(PIN,aLe,SQuav);//ん
  delay(SQuav);
  delay(SQuav);
  
  tone(PIN,aSi,SQuav);//つ
  delay(SQuav);
  tone(PIN,aLa,SQuav);//か
  delay(SQuav);
  tone(PIN,aFa,SQuav);//め!
  delay(SQuav);
  delay(QQuav);
  
  //45th bar
  tone(PIN,aFa,SQuav);//の
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//ぞ
  delay(DSQuav);
  tone(PIN,aSo,Quav);//む
  delay(Quav);
  tone(PIN,aFa,SQuav);//も
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//の
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//な
  delay(DSQuav);
  tone(PIN,aSo,Quav);//ら
  delay(Quav);
  
  tone(PIN,aFa,SQuav);//の
  delay(SQuav);
  delay(QQuav);
  
  //46th bar
  tone(PIN,aFa,SQuav);//こ
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//さ
  delay(DSQuav);
  tone(PIN,aSo,Quav);//ず
  delay(Quav);
  delay(QQuav);
  tone(PIN,aSo,SQuav);//か
  delay(SQuav);
  tone(PIN,aSo,SQuav);//が
  delay(SQuav);
  tone(PIN,aLa,SQuav);//や
  delay(SQuav);
  tone(PIN,aSi,SQuav);//け
  delay(SQuav);
  tone(PIN,bDa,SQuav);//る
  delay(SQuav);
  
  //47th bar
  tone(PIN,aLa,Quav);//じ
  delay(Quav);
  tone(PIN,aFa,Quav);//ぶ
  delay(Quav);
  tone(PIN,bMi,Quav);//ん
  delay(Quav);
  tone(PIN,bDa,Quav);//ら
  delay(Quav);
  
  //48th bar
  tone(PIN,bDa,Quav);//し
  delay(Quav);
  tone(PIN,bDa,SQuav);//さ
  delay(SQuav);
  tone(PIN,bLe,SQuav);//で
  delay(Quav);
  
  tone(PIN,aSi,SQuav);//し
  delay(SQuav);
  tone(PIN,aLa,SQuav);//ん
  delay(SQuav);
  tone(PIN,aFa,SQuav);//じ
  delay(SQuav);
  delay(QQuav);
  
  //49th bar
  tone(PIN,aFa,SQuav);//て
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//る
  delay(DSQuav);
  tone(PIN,aSo,Quav);//よ
  delay(Quav);
  tone(PIN,aFa,SQuav);//あ
  delay(SQuav);
  delay(QQuav);
  tone(PIN,aFa,SQuav);//の
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//ひ
  delay(DSQuav);
  tone(PIN,aSo,Quav);//の
  delay(Quav);
  
  tone(PIN,aFa,SQuav);//ち
  delay(SQuav);
  delay(QQuav);
  
  //50th bar
  tone(PIN,aFa,SQuav);//か
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//い
  delay(DSQuav);
  tone(PIN,aSo,Quav);//を
  delay(Quav);
  delay(QQuav);
  
  tone(PIN,aSo,SQuav);//こ
  delay(SQuav);
  tone(PIN,aSo,SQuav);//の
  delay(SQuav);
  tone(PIN,aLa,SQuav);//ひ
  delay(SQuav);
  tone(PIN,aSi,SQuav);//と
  delay(SQuav);
  tone(PIN,bDa,SQuav);//み
  delay(SQuav);
  
  //51th bar
  tone(PIN,aSo,Quat);//に
  delay(Quat);
  delay(DSQuav);
  
  tone(PIN,aSo,SQuav);//ひ
  delay(SQuav);
  tone(PIN,aLa,SQuav);//か
  delay(SQuav);
  tone(PIN,aSi,SQuav);//る
  delay(SQuav);
  tone(PIN,bDa,SQuav);//な
  delay(SQuav);
  
  //52th bar
  tone(PIN,aLa,Quav);//み
  delay(Quav);
  tone(PIN,aFa,Quav);//だ
  delay(Quav);
  tone(PIN,aLe,Quav);//そ
  delay(Quav);
  tone(PIN,aFa,Quav);//れ
  delay(Quav);
  delay(QQuav);
  
  //53th bar
  tone(PIN,aFa,SQuav);//さ
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//え
  delay(DSQuav);
  tone(PIN,aSo,Quav);//も
  delay(Quav);
  //delay(QQuav);
  tone(PIN,aSi,SQuav);//つ
  delay(SQuav);
  tone(PIN,aLa,SQuav);//よ
  delay(SQuav);
  tone(PIN,aFa,DSQuav);//さ
  delay(DSQuav);
  tone(PIN,aLe,Quav);//に
  delay(Quav);
  //delay(QQuav);
  tone(PIN,aFa,SQuav);//な
  delay(SQuav);
  
  //54th bar
  tone(PIN,aFa,SQuav);//る
  delay(SQuav);
  tone(PIN,aSo,DSQuav);//か
  delay(DSQuav);
  tone(PIN,aSo,Hal);//ら
  delay(Hal);
  
  //55th bar
  delay(Quat);
  
  //56th bar
}
