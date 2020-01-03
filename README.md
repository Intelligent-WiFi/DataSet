#### Data set description
Each row of data represents a user association record. 

The fields (from left to right, separated by '\t') are:

asso_id: The unique ID for the association record;
user_name: The user name, which has been be encrypted;
client_mac: MAC address of the association device;
ap_id: The unique ID of the AP that has been associated (7-id or 8-id, which means the AP is under the control of server 7 or server 8);
bytes: The traffic generated during this association, in bytes;
RSSI: Radio Signal Strength, where if the value equals '-1', it means there is no valid value is collected for this association record;
conn_time: The connection time of the association;
disconn_time: The disconnection time of the association.