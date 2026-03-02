# Server Metrics 2026-03-02 21:10:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 194383.0 (53h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3811832
telemt_connections_bad_total 56673
telemt_handshake_timeouts_total 313124
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 6953
telemt_me_reconnect_success_total 6955
telemt_me_route_drop_no_conn_total 1213908
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6817
telemt_desync_full_logged_total 2340
telemt_desync_suppressed_total 4477
telemt_desync_frames_bucket_total{bucket="1_2"} 2264
telemt_desync_frames_bucket_total{bucket="3_10"} 2253
telemt_desync_frames_bucket_total{bucket="gt_10"} 2300
telemt_pool_force_close_total 3401
telemt_pool_stale_pick_total 221735
telemt_me_writer_removed_unexpected_total 6888
telemt_me_writer_restored_same_endpoint_total 6250
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 3188183
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 80722558976 (75.18 GB)
telemt_user_octets_to_client{user="hello"} 1201344973772 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 194157.5 (53h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1723138
telemt_connections_bad_total 10239
telemt_handshake_timeouts_total 132501
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 7304
telemt_me_reconnect_success_total 7904
telemt_me_route_drop_no_conn_total 487347
telemt_desync_total 4341
telemt_desync_full_logged_total 1361
telemt_desync_suppressed_total 2980
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1584
telemt_pool_force_close_total 3428
telemt_pool_stale_pick_total 50901
telemt_me_writer_removed_unexpected_total 7665
telemt_me_writer_restored_same_endpoint_total 6763
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1337799
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 30471391148 (28.38 GB)
telemt_user_octets_to_client{user="hello"} 576572050772 (536.97 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 7047.5 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57125
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 474
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 1121
telemt_me_reconnect_success_total 1133
telemt_me_reader_eof_total 1126
telemt_me_route_drop_no_conn_total 22078
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1389
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_desync_total 244
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 1130
telemt_me_writer_restored_same_endpoint_total 1108
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 52318
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1846864572 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 19323192720 (18.00 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 7008.4 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52362
telemt_connections_bad_total 15927
telemt_handshake_timeouts_total 4091
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1434
telemt_me_reconnect_success_total 1457
telemt_me_reader_eof_total 1433
telemt_me_route_drop_no_conn_total 15324
telemt_me_route_drop_channel_closed_total 1
telemt_me_kdf_drift_total 1807
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_desync_total 99
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_force_close_total 23
telemt_me_writer_removed_unexpected_total 1453
telemt_me_writer_restored_same_endpoint_total 1423
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 30767
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 286966696 (273.67 MB)
telemt_user_octets_to_client{user="hello"} 11636785260 (10.84 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 194206.6 (53h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2783661
telemt_connections_bad_total 38611
telemt_handshake_timeouts_total 271072
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 6593
telemt_me_reconnect_success_total 7088
telemt_me_route_drop_no_conn_total 1028686
telemt_me_route_drop_channel_closed_total 45
telemt_desync_total 4537
telemt_desync_full_logged_total 1304
telemt_desync_suppressed_total 3233
telemt_desync_frames_bucket_total{bucket="1_2"} 1247
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1476
telemt_pool_force_close_total 3498
telemt_pool_stale_pick_total 115811
telemt_me_writer_removed_unexpected_total 6931
telemt_me_writer_restored_same_endpoint_total 6194
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 2323493
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 36895438468 (34.36 GB)
telemt_user_octets_to_client{user="hello"} 815638926232 (759.62 GB)
telemt_user_unique_ips_current{user="hello"} 37
```