# Server Metrics 2026-03-12 12:12:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22401.4 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761935
telemt_connections_bad_total 1580
telemt_handshake_timeouts_total 4688
telemt_upstream_connect_attempt_total 4401
telemt_upstream_connect_success_total 4373
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 7126
telemt_me_reconnect_success_total 3233
telemt_me_reader_eof_total 3475
telemt_me_idle_close_by_peer_total 3475
telemt_me_route_drop_no_conn_total 269561
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734607
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3772
telemt_desync_full_logged_total 955
telemt_desync_suppressed_total 2817
telemt_desync_frames_bucket_total{bucket="1_2"} 958
telemt_desync_frames_bucket_total{bucket="3_10"} 1369
telemt_desync_frames_bucket_total{bucket="gt_10"} 1445
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3388
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3220
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 734455
telemt_user_connections_current{user="hello"} 1599
telemt_user_octets_from_client{user="hello"} 12731648328 (11.86 GB)
telemt_user_octets_to_client{user="hello"} 204521297064 (190.48 GB)
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52021.8 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391230
telemt_connections_bad_total 4740
telemt_handshake_timeouts_total 20719
telemt_upstream_connect_attempt_total 12672
telemt_upstream_connect_success_total 12665
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1053
telemt_me_reconnect_attempts_total 9949
telemt_me_reconnect_success_total 9892
telemt_me_reader_eof_total 10516
telemt_me_idle_close_by_peer_total 10516
telemt_me_route_drop_no_conn_total 111828
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344397
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1109
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 745
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 295
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9983
telemt_me_writer_restored_same_endpoint_total 9883
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 344861
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 4693957571 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 122128718742 (113.74 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 52021.7 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890702
telemt_connections_bad_total 5035
telemt_handshake_timeouts_total 66976
telemt_upstream_connect_attempt_total 12773
telemt_upstream_connect_success_total 12768
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 858
telemt_me_reconnect_attempts_total 9907
telemt_me_reconnect_success_total 9824
telemt_me_reader_eof_total 10335
telemt_me_idle_close_by_peer_total 10335
telemt_me_route_drop_no_conn_total 215679
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602928
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2799
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1968
telemt_desync_frames_bucket_total{bucket="1_2"} 392
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 1425
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9847
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9783
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 603162
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 7900800352 (7.36 GB)
telemt_user_octets_to_client{user="hello"} 191227976677 (178.09 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 52022.1 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495893
telemt_connections_bad_total 7618
telemt_handshake_timeouts_total 46522
telemt_upstream_connect_attempt_total 13963
telemt_upstream_connect_success_total 13907
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 13963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1265
telemt_me_reconnect_attempts_total 11361
telemt_me_reconnect_success_total 11315
telemt_me_reader_eof_total 11972
telemt_me_idle_close_by_peer_total 11972
telemt_me_route_drop_no_conn_total 162092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411737
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11399
telemt_me_writer_restored_same_endpoint_total 11294
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 411560
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 4686448540 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 157933979172 (147.09 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52022.0 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555673
telemt_connections_bad_total 1695
telemt_handshake_timeouts_total 4322
telemt_upstream_connect_attempt_total 16956
telemt_upstream_connect_success_total 16756
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 16956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 959
telemt_me_reconnect_attempts_total 18723
telemt_me_reconnect_success_total 14156
telemt_me_reader_eof_total 14772
telemt_me_idle_close_by_peer_total 14772
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 184728
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519421
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2167
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 778
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14436
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 14129
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 519336
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 6051757648 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 129075740988 (120.21 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 139
```