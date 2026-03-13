# Server Metrics 2026-03-13 00:01:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 64974.6 (18h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1974930
telemt_connections_bad_total 26102
telemt_handshake_timeouts_total 21329
telemt_upstream_connect_attempt_total 12911
telemt_upstream_connect_success_total 12836
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1238
telemt_me_reconnect_attempts_total 18418
telemt_me_reconnect_success_total 9559
telemt_me_reader_eof_total 10341
telemt_me_idle_close_by_peer_total 10340
telemt_me_route_drop_no_conn_total 768487
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1836345
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8614
telemt_desync_full_logged_total 2249
telemt_desync_suppressed_total 6365
telemt_desync_frames_bucket_total{bucket="1_2"} 2270
telemt_desync_frames_bucket_total{bucket="3_10"} 3103
telemt_desync_frames_bucket_total{bucket="gt_10"} 3241
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9971
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9546
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 1835808
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 27367814736 (25.49 GB)
telemt_user_octets_to_client{user="hello"} 649223317060 (604.64 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94595.3 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815608
telemt_connections_bad_total 11748
telemt_handshake_timeouts_total 31660
telemt_upstream_connect_attempt_total 24032
telemt_upstream_connect_success_total 24003
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 24032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3433
telemt_me_reconnect_attempts_total 17715
telemt_me_reconnect_success_total 17617
telemt_me_reader_eof_total 18745
telemt_me_idle_close_by_peer_total 18745
telemt_me_route_drop_no_conn_total 263389
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3022
telemt_desync_full_logged_total 945
telemt_desync_suppressed_total 2077
telemt_desync_frames_bucket_total{bucket="1_2"} 1203
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17790
telemt_me_writer_restored_same_endpoint_total 17608
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 739807
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 12153876256 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 283979312439 (264.48 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 94595.0 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1698424
telemt_connections_bad_total 8351
telemt_handshake_timeouts_total 113430
telemt_upstream_connect_attempt_total 22004
telemt_upstream_connect_success_total 21994
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 22004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1570
telemt_me_reconnect_attempts_total 18157
telemt_me_reconnect_success_total 16898
telemt_me_reader_eof_total 17887
telemt_me_idle_close_by_peer_total 17886
telemt_me_route_drop_no_conn_total 556783
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1330335
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4975
telemt_desync_full_logged_total 1527
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2384
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 17060
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16857
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 1329937
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 19887732652 (18.52 GB)
telemt_user_octets_to_client{user="hello"} 487240130397 (453.78 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 94595.2 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1056248
telemt_connections_bad_total 13026
telemt_handshake_timeouts_total 71685
telemt_upstream_connect_attempt_total 33244
telemt_upstream_connect_success_total 30983
telemt_upstream_connect_fail_total 2124
telemt_upstream_connect_attempts_per_request{bucket="1"} 32970
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2123
telemt_me_keepalive_timeout_total 11255
telemt_me_reconnect_attempts_total 28226
telemt_me_reconnect_success_total 20388
telemt_me_reader_eof_total 22071
telemt_me_idle_close_by_peer_total 22064
telemt_me_route_drop_no_conn_total 372103
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 909931
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1891
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20755
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20366
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 915151
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 14347217213 (13.36 GB)
telemt_user_octets_to_client{user="hello"} 363417020986 (338.46 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94595.2 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1169194
telemt_connections_bad_total 12559
telemt_handshake_timeouts_total 9289
telemt_upstream_connect_attempt_total 28647
telemt_upstream_connect_success_total 28288
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 28647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 1820
telemt_me_reconnect_attempts_total 34596
telemt_me_reconnect_success_total 23554
telemt_me_reader_eof_total 24799
telemt_me_idle_close_by_peer_total 24799
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 436828
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078335
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4053
telemt_desync_full_logged_total 1424
telemt_desync_suppressed_total 2629
telemt_desync_frames_bucket_total{bucket="1_2"} 1182
telemt_desync_frames_bucket_total{bucket="3_10"} 1350
telemt_desync_frames_bucket_total{bucket="gt_10"} 1521
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 24174
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23509
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 1078192
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 13559509044 (12.63 GB)
telemt_user_octets_to_client{user="hello"} 378825183472 (352.81 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 48
```