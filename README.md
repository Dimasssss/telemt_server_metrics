# Server Metrics 2026-03-11 10:26:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 71934.7 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1578197
telemt_connections_bad_total 24742
telemt_handshake_timeouts_total 41485
telemt_upstream_connect_attempt_total 14867
telemt_upstream_connect_success_total 14858
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 799
telemt_me_reconnect_attempts_total 22933
telemt_me_reconnect_success_total 11243
telemt_me_reader_eof_total 12161
telemt_me_idle_close_by_peer_total 12161
telemt_me_route_drop_no_conn_total 581896
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1432025
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7139
telemt_desync_full_logged_total 1967
telemt_desync_suppressed_total 5172
telemt_desync_frames_bucket_total{bucket="1_2"} 1885
telemt_desync_frames_bucket_total{bucket="3_10"} 2690
telemt_desync_frames_bucket_total{bucket="gt_10"} 2564
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11718
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11237
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 1430605
telemt_user_connections_current{user="hello"} 1138
telemt_user_octets_from_client{user="hello"} 18580765996 (17.30 GB)
telemt_user_octets_to_client{user="hello"} 409045977428 (380.95 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71991.5 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604058
telemt_connections_bad_total 10183
telemt_handshake_timeouts_total 36776
telemt_upstream_connect_attempt_total 23933
telemt_upstream_connect_success_total 21003
telemt_upstream_connect_fail_total 2930
telemt_upstream_connect_attempts_per_request{bucket="1"} 23933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2930
telemt_me_keepalive_timeout_total 2145
telemt_me_reconnect_attempts_total 15312
telemt_me_reconnect_success_total 14469
telemt_me_reader_eof_total 15322
telemt_me_idle_close_by_peer_total 15320
telemt_me_route_drop_no_conn_total 248097
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511263
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2301
telemt_desync_full_logged_total 714
telemt_desync_suppressed_total 1587
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 827
telemt_desync_frames_bucket_total{bucket="gt_10"} 713
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14647
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14447
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 513490
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 5009850574 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 143382339376 (133.54 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 71991.4 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046251
telemt_connections_bad_total 7700
telemt_handshake_timeouts_total 101147
telemt_upstream_connect_attempt_total 19443
telemt_upstream_connect_success_total 19203
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 19443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 808
telemt_me_reconnect_attempts_total 28153
telemt_me_reconnect_success_total 14536
telemt_me_reader_eof_total 15615
telemt_me_idle_close_by_peer_total 15615
telemt_me_route_drop_no_conn_total 346053
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897416
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2548
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1796
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 943
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 15147
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14525
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 611
telemt_user_connections_total{user="hello"} 898225
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 10587797541 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 274816875481 (255.94 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 71992.0 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 762364
telemt_connections_bad_total 67738
telemt_handshake_timeouts_total 73009
telemt_upstream_connect_attempt_total 19692
telemt_upstream_connect_success_total 19692
telemt_upstream_connect_attempts_per_request{bucket="1"} 19692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 17172
telemt_me_reconnect_success_total 16115
telemt_me_reader_eof_total 17112
telemt_me_idle_close_by_peer_total 17111
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 240049
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599123
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1302
telemt_desync_full_logged_total 498
telemt_desync_suppressed_total 804
telemt_desync_frames_bucket_total{bucket="1_2"} 451
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16306
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16091
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 598494
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 6884699832 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 172700721088 (160.84 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71991.7 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812244
telemt_connections_bad_total 6085
telemt_handshake_timeouts_total 7764
telemt_upstream_connect_attempt_total 19289
telemt_upstream_connect_success_total 19209
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 19289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 811
telemt_me_reconnect_attempts_total 19311
telemt_me_reconnect_success_total 15516
telemt_me_reader_eof_total 16409
telemt_me_idle_close_by_peer_total 16409
telemt_me_route_drop_no_conn_total 281272
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737657
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3080
telemt_desync_full_logged_total 1152
telemt_desync_suppressed_total 1928
telemt_desync_frames_bucket_total{bucket="1_2"} 1069
telemt_desync_frames_bucket_total{bucket="3_10"} 1246
telemt_desync_frames_bucket_total{bucket="gt_10"} 765
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 15831
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15516
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 737376
telemt_user_connections_current{user="hello"} 775
telemt_user_octets_from_client{user="hello"} 11324899383 (10.55 GB)
telemt_user_octets_to_client{user="hello"} 269907804050 (251.37 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 97
```