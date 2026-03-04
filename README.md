# Server Metrics 2026-03-04 09:24:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 44022.2 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584164
telemt_connections_bad_total 10489
telemt_handshake_timeouts_total 6859
telemt_upstream_connect_attempt_total 28289
telemt_upstream_connect_success_total 28166
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 28166
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 303
telemt_me_reconnect_attempts_total 6044
telemt_me_reconnect_success_total 6003
telemt_me_reader_eof_total 6174
telemt_me_idle_close_by_peer_total 6174
telemt_me_route_drop_no_conn_total 204438
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1006
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 6174
telemt_me_writer_restored_same_endpoint_total 5982
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 483447
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 5456874968 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 142018743944 (132.27 GB)
telemt_user_unique_ips_current{user="hello"} 96
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 44018.7 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231473
telemt_connections_bad_total 1990
telemt_handshake_timeouts_total 24555
telemt_upstream_connect_attempt_total 91018
telemt_upstream_connect_success_total 89730
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 89724
telemt_upstream_connect_attempts_per_request{bucket="2"} 612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 1297
telemt_me_reconnect_attempts_total 52756
telemt_me_reconnect_success_total 52675
telemt_me_reader_eof_total 54029
telemt_me_idle_close_by_peer_total 54028
telemt_me_route_drop_no_conn_total 109115
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 514
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 2
telemt_pool_force_close_total 140
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 54109
telemt_me_writer_restored_same_endpoint_total 52650
telemt_me_writer_removed_unexpected_minus_restored_total 1459
telemt_user_connections_total{user="hello"} 176402
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 2045068916 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 61945787052 (57.69 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 44017.5 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482975
telemt_connections_bad_total 134395
telemt_handshake_timeouts_total 14717
telemt_upstream_connect_attempt_total 63282
telemt_upstream_connect_success_total 62882
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 62881
telemt_upstream_connect_attempts_per_request{bucket="2"} 192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 842
telemt_me_reconnect_attempts_total 28505
telemt_me_reconnect_success_total 28429
telemt_me_reader_eof_total 29996
telemt_me_idle_close_by_peer_total 29993
telemt_me_route_drop_no_conn_total 161341
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 725
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 30007
telemt_me_writer_restored_same_endpoint_total 28408
telemt_me_writer_removed_unexpected_minus_restored_total 1599
telemt_user_connections_total{user="hello"} 318166
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 3144159768 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 115336581988 (107.42 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 44016.5 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310122
telemt_connections_bad_total 21699
telemt_handshake_timeouts_total 50241
telemt_upstream_connect_attempt_total 32332
telemt_upstream_connect_success_total 32201
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 32201
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 6577
telemt_me_reconnect_success_total 6556
telemt_me_reader_eof_total 6681
telemt_me_idle_close_by_peer_total 6681
telemt_me_route_drop_no_conn_total 87845
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 182
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 12
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6681
telemt_me_writer_restored_same_endpoint_total 6535
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 217416
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 2411072524 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 75955928456 (70.74 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 44015.2 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436840
telemt_connections_bad_total 6468
telemt_handshake_timeouts_total 132133
telemt_upstream_connect_attempt_total 67744
telemt_upstream_connect_success_total 67325
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 67325
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 892
telemt_me_reconnect_attempts_total 33507
telemt_me_reconnect_success_total 33479
telemt_me_reader_eof_total 35156
telemt_me_idle_close_by_peer_total 35155
telemt_me_route_drop_no_conn_total 133272
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 375
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 5
telemt_pool_force_close_total 233
telemt_pool_stale_pick_total 2808
telemt_me_writer_removed_unexpected_total 35168
telemt_me_writer_restored_same_endpoint_total 33454
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 281837
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 3936024364 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 70138361004 (65.32 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 57
```