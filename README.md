# Input_lite
cross platform input library
```c++

    SL::Input_Lite::SendKeyDown('H');
    SL::Input_Lite::SendKeyUp('H');
    SL::Input_Lite::SendKeyDown('e');
    SL::Input_Lite::SendKeyUp('e');
    SL::Input_Lite::SendKeyDown('l');
    SL::Input_Lite::SendKeyUp('l');
    SL::Input_Lite::SendKey('o');
    SL::Input_Lite::SendKey('o');
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ENTER);
    //UNICODE SUPPORT!
    SL::Input_Lite::SendKeyDown((wchar_t)294);//the letter Ħ
    SL::Input_Lite::SendKeyDown((wchar_t)274);//the letter Ē
    SL::Input_Lite::SendKeyDown((wchar_t)315);//the letter Ļ
    SL::Input_Lite::SendKeyDown((wchar_t)315);//the letter Ļ
    SL::Input_Lite::SendKeyDown((wchar_t)526);//the letter Ȏ
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ENTER);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::TAB);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::TAB);
    SL::Input_Lite::SendKeys("Hey there");
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ENTER);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::TAB);
    SL::Input_Lite::SendKeys(std::string("this is a std::string"));
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ENTER);
    //unicode
    SL::Input_Lite::SendKeys(L"ĦĒĻĻȎ");
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ENTER);
    SL::Input_Lite::SendKeys(std::wstring(L"ĦĒĻĻȎ"));
    //SPECIAL KEYS
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ENTER);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::NUMPAD0);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::CAPSLOCK);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::TAB);

    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ARROWLEFT);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ARROWLEFT);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ARROWLEFT);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ARROWLEFT);
    SL::Input_Lite::SendKey(SL::Input_Lite::SpecialKeyCodes::ARROWLEFT);

```
