# Server Metrics 2026-03-04 16:19:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 68929.7 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1322779
telemt_connections_bad_total 18532
telemt_handshake_timeouts_total 22883
telemt_upstream_connect_attempt_total 40153
telemt_upstream_connect_success_total 39966
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 39966
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 453
telemt_me_reconnect_attempts_total 8534
telemt_me_reconnect_success_total 8467
telemt_me_reader_eof_total 8744
telemt_me_idle_close_by_peer_total 8743
telemt_me_route_drop_no_conn_total 511919
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2814
telemt_desync_full_logged_total 895
telemt_desync_suppressed_total 1919
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 1052
telemt_desync_frames_bucket_total{bucket="gt_10"} 951
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8744
telemt_me_writer_restored_same_endpoint_total 8445
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 1075299
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 14384238464 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 359815284512 (335.10 GB)
telemt_user_unique_ips_current{user="hello"} 114
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 68926.2 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502168
telemt_connections_bad_total 4701
telemt_handshake_timeouts_total 30673
telemt_upstream_connect_attempt_total 124158
telemt_upstream_connect_success_total 122404
telemt_upstream_connect_fail_total 839
telemt_upstream_connect_attempts_per_request{bucket="1"} 122398
telemt_upstream_connect_attempts_per_request{bucket="2"} 845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 839
telemt_me_keepalive_timeout_total 1632
telemt_me_reconnect_attempts_total 67709
telemt_me_reconnect_success_total 67602
telemt_me_reader_eof_total 69339
telemt_me_idle_close_by_peer_total 69338
telemt_me_route_drop_no_conn_total 205558
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1297
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 905
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 511
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 136
telemt_me_writer_removed_unexpected_total 69419
telemt_me_writer_restored_same_endpoint_total 67576
telemt_me_writer_removed_unexpected_minus_restored_total 1843
telemt_user_connections_total{user="hello"} 402422
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 6080575100 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 126623961028 (117.93 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 68925.0 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014603
telemt_connections_bad_total 203944
telemt_handshake_timeouts_total 30318
telemt_upstream_connect_attempt_total 90198
telemt_upstream_connect_success_total 89580
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 89579
telemt_upstream_connect_attempts_per_request{bucket="2"} 300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_timeout_total 1176
telemt_me_reconnect_attempts_total 40245
telemt_me_reconnect_success_total 40138
telemt_me_reader_eof_total 42262
telemt_me_idle_close_by_peer_total 42257
telemt_me_route_drop_no_conn_total 371009
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 283
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2128
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 635
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 802
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42275
telemt_me_writer_restored_same_endpoint_total 40116
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 733380
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 14442420752 (13.45 GB)
telemt_user_octets_to_client{user="hello"} 251376999504 (234.11 GB)
telemt_user_unique_ips_current{user="hello"} 65
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 15602.3 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255327
telemt_connections_bad_total 30053
telemt_handshake_timeouts_total 6453
telemt_upstream_connect_attempt_total 6318
telemt_upstream_connect_success_total 6318
telemt_upstream_connect_attempts_per_request{bucket="1"} 6318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2753
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 870
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 84742
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 242
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 888
telemt_me_writer_restored_same_endpoint_total 857
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 209855
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 2738092904 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 80458572456 (74.93 GB)
telemt_user_unique_ips_current{user="hello"} 75
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 15961.8 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273960
telemt_connections_bad_total 2521
telemt_handshake_timeouts_total 4032
telemt_upstream_connect_attempt_total 7751
telemt_upstream_connect_success_total 7712
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 7712
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 1337
telemt_me_reconnect_success_total 1342
telemt_me_reader_eof_total 1369
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 106207
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 537
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1369
telemt_me_writer_restored_same_endpoint_total 1321
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 235785
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 3825544220 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 70308264596 (65.48 GB)
telemt_user_unique_ips_current{user="hello"} 51
```