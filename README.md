# Server Metrics 2026-03-02 19:27:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.3

telemt_uptime_seconds 188209.5 (52h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3715682
telemt_connections_bad_total 55886
telemt_handshake_timeouts_total 310669
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 6513
telemt_me_reconnect_success_total 6514
telemt_me_route_drop_no_conn_total 1184118
telemt_me_route_drop_channel_closed_total 23
telemt_desync_total 6571
telemt_desync_full_logged_total 2261
telemt_desync_suppressed_total 4310
telemt_desync_frames_bucket_total{bucket="1_2"} 2181
telemt_desync_frames_bucket_total{bucket="3_10"} 2170
telemt_desync_frames_bucket_total{bucket="gt_10"} 2220
telemt_pool_force_close_total 3277
telemt_pool_stale_pick_total 213304
telemt_me_writer_removed_unexpected_total 6447
telemt_me_writer_restored_same_endpoint_total 5822
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 3100638
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 75201940980 (70.04 GB)
telemt_user_octets_to_client{user="hello"} 1164020533932 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 84
```

## server2

```
telemt 3.1.3

telemt_uptime_seconds 187983.4 (52h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1679877
telemt_connections_bad_total 10214
telemt_handshake_timeouts_total 131346
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 7047
telemt_me_reconnect_success_total 7659
telemt_me_route_drop_no_conn_total 470683
telemt_desync_total 3984
telemt_desync_full_logged_total 1296
telemt_desync_suppressed_total 2688
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 1670
telemt_desync_frames_bucket_total{bucket="gt_10"} 1474
telemt_pool_force_close_total 3296
telemt_pool_stale_pick_total 49281
telemt_me_writer_removed_unexpected_total 7420
telemt_me_writer_restored_same_endpoint_total 6554
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 1296322
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 29600722260 (27.57 GB)
telemt_user_octets_to_client{user="hello"} 557686140520 (519.39 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server3

```
telemt 3.1.4

telemt_uptime_seconds 873.6 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9236
telemt_handshake_timeouts_total 107
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 39
telemt_me_reader_eof_total 19
telemt_me_route_drop_no_conn_total 1603
telemt_me_kdf_drift_total 58
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_desync_total 21
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 8536
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 1524079612 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 1587416712 (1.48 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.1.4

telemt_uptime_seconds 834.7 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14732
telemt_connections_bad_total 7094
telemt_handshake_timeouts_total 583
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 52
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 56
telemt_me_route_drop_no_conn_total 1307
telemt_me_kdf_drift_total 93
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_me_writer_removed_unexpected_total 56
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 6508
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 17297820 (16.50 MB)
telemt_user_octets_to_client{user="hello"} 1423286504 (1.33 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server5

```
telemt 3.1.3

telemt_uptime_seconds 188033.0 (52h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2699915
telemt_connections_bad_total 38553
telemt_handshake_timeouts_total 269834
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 6434
telemt_me_reconnect_success_total 6918
telemt_me_route_drop_no_conn_total 993733
telemt_me_route_drop_channel_closed_total 43
telemt_desync_total 4358
telemt_desync_full_logged_total 1252
telemt_desync_suppressed_total 3106
telemt_desync_frames_bucket_total{bucket="1_2"} 1193
telemt_desync_frames_bucket_total{bucket="3_10"} 1741
telemt_desync_frames_bucket_total{bucket="gt_10"} 1424
telemt_pool_force_close_total 3410
telemt_pool_stale_pick_total 105001
telemt_me_writer_removed_unexpected_total 6761
telemt_me_writer_restored_same_endpoint_total 6044
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 2245907
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 35174730224 (32.76 GB)
telemt_user_octets_to_client{user="hello"} 798815356876 (743.95 GB)
telemt_user_unique_ips_current{user="hello"} 61
```