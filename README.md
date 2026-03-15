# Server Metrics 2026-03-15 15:31:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 62236.5 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2010855
telemt_connections_bad_total 109084
telemt_handshake_timeouts_total 22840
telemt_upstream_connect_attempt_total 12430
telemt_upstream_connect_success_total 12375
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 12430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14123
telemt_me_reconnect_success_total 9229
telemt_me_reader_eof_total 9866
telemt_me_idle_close_by_peer_total 9866
telemt_me_route_drop_no_conn_total 691563
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1701628
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6475
telemt_desync_full_logged_total 1787
telemt_desync_suppressed_total 4688
telemt_desync_frames_bucket_total{bucket="1_2"} 1596
telemt_desync_frames_bucket_total{bucket="3_10"} 2490
telemt_desync_frames_bucket_total{bucket="gt_10"} 2389
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9531
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9218
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 1701140
telemt_user_connections_current{user="hello"} 2410
telemt_user_octets_from_client{user="hello"} 25006963896 (23.29 GB)
telemt_user_octets_to_client{user="hello"} 657151953128 (612.02 GB)
telemt_user_unique_ips_current{user="hello"} 681
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 62237.3 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802711
telemt_connections_bad_total 42901
telemt_handshake_timeouts_total 59142
telemt_upstream_connect_attempt_total 15710
telemt_upstream_connect_success_total 15634
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 15710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12247
telemt_me_reconnect_success_total 12149
telemt_me_reader_eof_total 12837
telemt_me_idle_close_by_peer_total 12837
telemt_me_route_drop_no_conn_total 201579
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610260
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2074
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1377
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12306
telemt_me_writer_restored_same_endpoint_total 12137
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 610502
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 8521209635 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 229652226836 (213.88 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 62237.2 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1794493
telemt_connections_bad_total 47497
telemt_handshake_timeouts_total 178966
telemt_upstream_connect_attempt_total 13629
telemt_upstream_connect_success_total 13564
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11657
telemt_me_reconnect_success_total 10396
telemt_me_reader_eof_total 11015
telemt_me_idle_close_by_peer_total 11015
telemt_me_route_drop_no_conn_total 470672
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083356
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2675
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 1691
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10580
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10377
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 1079356
telemt_user_connections_current{user="hello"} 1452
telemt_user_octets_from_client{user="hello"} 15562046016 (14.49 GB)
telemt_user_octets_to_client{user="hello"} 386395694232 (359.86 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 62237.2 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847059
telemt_connections_bad_total 75844
telemt_handshake_timeouts_total 42237
telemt_upstream_connect_attempt_total 168003
telemt_upstream_connect_success_total 167494
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 168003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52724
telemt_me_reconnect_success_total 12284
telemt_me_reader_eof_total 13891
telemt_me_idle_close_by_peer_total 13891
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 187162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499715
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1352
telemt_desync_full_logged_total 353
telemt_desync_suppressed_total 999
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 544
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 13670
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12250
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1386
telemt_user_connections_total{user="hello"} 651370
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 12900788842 (12.01 GB)
telemt_user_octets_to_client{user="hello"} 229325641381 (213.58 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 62238.1 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857635
telemt_connections_bad_total 9432
telemt_handshake_timeouts_total 18595
telemt_upstream_connect_attempt_total 13866
telemt_upstream_connect_success_total 13789
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14326
telemt_me_reconnect_success_total 10644
telemt_me_reader_eof_total 11356
telemt_me_idle_close_by_peer_total 11356
telemt_me_route_drop_no_conn_total 213487
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705273
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2458
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1627
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 944
telemt_desync_frames_bucket_total{bucket="gt_10"} 766
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10884
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10636
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 705313
telemt_user_connections_current{user="hello"} 843
telemt_user_octets_from_client{user="hello"} 8716729400 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 255698023056 (238.14 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 129
```