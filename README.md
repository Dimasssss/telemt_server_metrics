# Server Metrics 2026-03-11 09:24:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 68261.2 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1451567
telemt_connections_bad_total 19206
telemt_handshake_timeouts_total 40535
telemt_upstream_connect_attempt_total 14217
telemt_upstream_connect_success_total 14208
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 778
telemt_me_reconnect_attempts_total 22459
telemt_me_reconnect_success_total 10771
telemt_me_reader_eof_total 11671
telemt_me_idle_close_by_peer_total 11671
telemt_me_route_drop_no_conn_total 535516
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1317230
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6425
telemt_desync_full_logged_total 1780
telemt_desync_suppressed_total 4645
telemt_desync_frames_bucket_total{bucket="1_2"} 1693
telemt_desync_frames_bucket_total{bucket="3_10"} 2442
telemt_desync_frames_bucket_total{bucket="gt_10"} 2290
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11241
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10765
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 1315841
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 17361296912 (16.17 GB)
telemt_user_octets_to_client{user="hello"} 378068141296 (352.10 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68317.9 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557868
telemt_connections_bad_total 9519
telemt_handshake_timeouts_total 30669
telemt_upstream_connect_attempt_total 23148
telemt_upstream_connect_success_total 20221
telemt_upstream_connect_fail_total 2927
telemt_upstream_connect_attempts_per_request{bucket="1"} 23148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2927
telemt_me_keepalive_timeout_total 2098
telemt_me_reconnect_attempts_total 14705
telemt_me_reconnect_success_total 13869
telemt_me_reader_eof_total 14680
telemt_me_idle_close_by_peer_total 14678
telemt_me_route_drop_no_conn_total 233511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473013
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2204
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1526
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 791
telemt_desync_frames_bucket_total{bucket="gt_10"} 678
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 14031
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13847
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 475250
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 4642171574 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 128443658136 (119.62 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 68317.8 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 973587
telemt_connections_bad_total 7469
telemt_handshake_timeouts_total 96650
telemt_upstream_connect_attempt_total 18495
telemt_upstream_connect_success_total 18268
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 18494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 769
telemt_me_reconnect_attempts_total 26152
telemt_me_reconnect_success_total 13787
telemt_me_reader_eof_total 14807
telemt_me_idle_close_by_peer_total 14807
telemt_me_route_drop_no_conn_total 318953
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 831189
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2378
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1673
telemt_desync_frames_bucket_total{bucket="1_2"} 574
telemt_desync_frames_bucket_total{bucket="3_10"} 868
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 14352
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13776
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 565
telemt_user_connections_total{user="hello"} 832063
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 9876487497 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 252533739273 (235.19 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 68318.3 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710441
telemt_connections_bad_total 64137
telemt_handshake_timeouts_total 68851
telemt_upstream_connect_attempt_total 18816
telemt_upstream_connect_success_total 18816
telemt_upstream_connect_attempts_per_request{bucket="1"} 18816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 707
telemt_me_reconnect_attempts_total 16471
telemt_me_reconnect_success_total 15417
telemt_me_reader_eof_total 16372
telemt_me_idle_close_by_peer_total 16371
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 222015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555601
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1251
telemt_desync_full_logged_total 473
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 15599
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15394
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 554975
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 6494827556 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 156905251480 (146.13 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68317.8 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752550
telemt_connections_bad_total 5983
telemt_handshake_timeouts_total 7151
telemt_upstream_connect_attempt_total 18528
telemt_upstream_connect_success_total 18454
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 18528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 766
telemt_me_reconnect_attempts_total 18730
telemt_me_reconnect_success_total 14938
telemt_me_reader_eof_total 15796
telemt_me_idle_close_by_peer_total 15796
telemt_me_route_drop_no_conn_total 257354
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681652
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2920
telemt_desync_full_logged_total 1106
telemt_desync_suppressed_total 1814
telemt_desync_frames_bucket_total{bucket="1_2"} 1023
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15248
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14938
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 681336
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 10837768115 (10.09 GB)
telemt_user_octets_to_client{user="hello"} 244287606926 (227.51 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 108
```