package me.StevenLaswon.TotalFreedomMod.Commands;

import me.StevenLawson.TotalFreedomMod.Commands.AdminLevel;
import me.StevenLawson.TotalFreedomMod.Commands.CommandParameters;
import me.StevenLawson.TotalFreedomMod.Commands.CommandPermissions;
import me.StevenLawson.TotalFreedomMod.Commands.SourceType;
import me.StevenLawson.TotalFreedomMod.Commands.TFM_Command;
import org.bukkit.ChatColor;
import org.bukkit.command.Command;
import org.bukkit.command.CommandSender;
import org.bukkit.entity.Player;


@CommandPermissions(level = AdminLevel.ALL, source = SourceType.BOTH)
@CommandParameters(description = "Information about the PacksFreedomMod plugin.", usage = "/<command>", aliases = "ai")
public class Command_pfm extends TFM_Command {

    @Override
    public boolean run(CommandSender sender, Player sender_p, Command cmd, String commandLabel, String[] args, boolean senderIsConsole) {

        playerMsg(ChatColor.GOLD + "PacksFreedomMod made for the server 'PacksFreedom'");
        playerMsg(ChatColor.GOLD + "Version 1.0, built 05/21/14 20:43 PM by packeretteswan");
        playerMsg(ChatColor.GRAY + "Running on PacksFreedom");
        playerMsg(ChatColor.GOLD + "Created by Madgeek1450 and DarthSalamon later modifed by packeretteswan for PacksFreedom");
        playerMsg(ChatColor.GREEN + "Visit " + ChatColor.AQUA + "http://packsfreedom.icyboards.net/" + ChatColor.GREEN + " for more information.", ChatColor.GREEN);
        return true;
    }
}
