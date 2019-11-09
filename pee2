#!/usr/bin/env python3
import requests
import discord
from discord import Webhook, RequestsWebhookAdapter, File
 
# Create webhook
webhook = Webhook.partial(WEBHOOK_ID, WEBHOOK_TOKEN,\
 adapter=RequestsWebhookAdapter())
 
# Send temperature as text
webhook.send(&quot;Current Temp: &quot; + CURRENT_TEMP)
 
# Upload image to server
webhook.send(file=discord.File(&quot;latest_img.jpg&quot;))
