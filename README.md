# Server Metrics 2026-03-12 20:32:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 52423.0 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1802445
telemt_connections_bad_total 20723
telemt_handshake_timeouts_total 19733
telemt_upstream_connect_attempt_total 10218
telemt_upstream_connect_success_total 10157
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 581
telemt_me_reconnect_attempts_total 16341
telemt_me_reconnect_success_total 7492
telemt_me_reader_eof_total 8110
telemt_me_idle_close_by_peer_total 8109
telemt_me_route_drop_no_conn_total 710214
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1682417
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8260
telemt_desync_full_logged_total 2132
telemt_desync_suppressed_total 6128
telemt_desync_frames_bucket_total{bucket="1_2"} 2161
telemt_desync_frames_bucket_total{bucket="3_10"} 2986
telemt_desync_frames_bucket_total{bucket="gt_10"} 3113
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7877
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7479
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 1681902
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 25876031620 (24.10 GB)
telemt_user_octets_to_client{user="hello"} 582462077952 (542.46 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82043.3 (22h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759055
telemt_connections_bad_total 10734
telemt_handshake_timeouts_total 30318
telemt_upstream_connect_attempt_total 20790
telemt_upstream_connect_success_total 20761
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3385
telemt_me_reconnect_attempts_total 15078
telemt_me_reconnect_success_total 14988
telemt_me_reader_eof_total 15936
telemt_me_idle_close_by_peer_total 15936
telemt_me_route_drop_no_conn_total 243990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 685006
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2934
telemt_desync_full_logged_total 899
telemt_desync_suppressed_total 2035
telemt_desync_frames_bucket_total{bucket="1_2"} 1135
telemt_desync_frames_bucket_total{bucket="3_10"} 973
telemt_desync_frames_bucket_total{bucket="gt_10"} 826
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15141
telemt_me_writer_restored_same_endpoint_total 14979
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 686878
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 11742805660 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 261837110279 (243.85 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 82043.2 (22h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1567946
telemt_connections_bad_total 7539
telemt_handshake_timeouts_total 107414
telemt_upstream_connect_attempt_total 19281
telemt_upstream_connect_success_total 19274
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 19280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1203
telemt_me_reconnect_attempts_total 16037
telemt_me_reconnect_success_total 14789
telemt_me_reader_eof_total 15608
telemt_me_idle_close_by_peer_total 15607
telemt_me_route_drop_no_conn_total 518388
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1209157
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4816
telemt_desync_full_logged_total 1481
telemt_desync_suppressed_total 3335
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 1743
telemt_desync_frames_bucket_total{bucket="gt_10"} 2309
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 14929
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14748
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 1208765
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 19077592344 (17.77 GB)
telemt_user_octets_to_client{user="hello"} 451351970897 (420.35 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 82043.8 (22h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 963645
telemt_connections_bad_total 12970
telemt_handshake_timeouts_total 70640
telemt_upstream_connect_attempt_total 20943
telemt_upstream_connect_success_total 20860
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 20943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1671
telemt_me_reconnect_attempts_total 24466
telemt_me_reconnect_success_total 16740
telemt_me_reader_eof_total 17880
telemt_me_idle_close_by_peer_total 17880
telemt_me_route_drop_no_conn_total 343728
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 836366
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1766
telemt_desync_full_logged_total 590
telemt_desync_suppressed_total 1176
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 586
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 17116
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16719
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 376
telemt_user_connections_total{user="hello"} 835716
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 13079173080 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 341978310308 (318.49 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82043.5 (22h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1081989
telemt_connections_bad_total 12381
telemt_handshake_timeouts_total 8953
telemt_upstream_connect_attempt_total 25513
telemt_upstream_connect_success_total 25202
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 25513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 32102
telemt_me_reconnect_success_total 21064
telemt_me_reader_eof_total 22137
telemt_me_idle_close_by_peer_total 22137
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 405000
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 992967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3719
telemt_desync_full_logged_total 1302
telemt_desync_suppressed_total 2417
telemt_desync_frames_bucket_total{bucket="1_2"} 1066
telemt_desync_frames_bucket_total{bucket="3_10"} 1236
telemt_desync_frames_bucket_total{bucket="gt_10"} 1417
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 21649
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 21020
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 992836
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 12383880528 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 347525310444 (323.66 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 73
```