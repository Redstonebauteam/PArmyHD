# PArmyHD
Code (Text):
public Bot bot; 
public final String TOKEN = "[DmQQW_9nUMh1eyKxuA-hJJkfGBcTHaMV]"; 
public final String PREFIX = "!"; 

@Override 
public void onEnable() { 
    bot = new Bot(TOKEN, PREFIX); 
    bot.setBotThread(new ThreadHandle()); 
    bot.setConsoleCommandManager(new CommandConsoleManager()); 
}
