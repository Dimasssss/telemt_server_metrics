# Server Metrics 2026-03-11 11:42:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 76528.5 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1731052
telemt_connections_bad_total 25371
telemt_handshake_timeouts_total 44738
telemt_upstream_connect_attempt_total 15953
telemt_upstream_connect_success_total 15944
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 826
telemt_me_reconnect_attempts_total 24916
telemt_me_reconnect_success_total 12096
telemt_me_reader_eof_total 13088
telemt_me_idle_close_by_peer_total 13088
telemt_me_route_drop_no_conn_total 636677
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1575423
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8337
telemt_desync_full_logged_total 2241
telemt_desync_suppressed_total 6096
telemt_desync_frames_bucket_total{bucket="1_2"} 2095
telemt_desync_frames_bucket_total{bucket="3_10"} 3190
telemt_desync_frames_bucket_total{bucket="gt_10"} 3052
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12621
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12090
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 1573987
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 20365088076 (18.97 GB)
telemt_user_octets_to_client{user="hello"} 447865465700 (417.11 GB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76585.4 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654859
telemt_connections_bad_total 11461
telemt_handshake_timeouts_total 41302
telemt_upstream_connect_attempt_total 25040
telemt_upstream_connect_success_total 22101
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 25040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 2191
telemt_me_reconnect_attempts_total 16163
telemt_me_reconnect_success_total 15313
telemt_me_reader_eof_total 16207
telemt_me_idle_close_by_peer_total 16205
telemt_me_route_drop_no_conn_total 264614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555071
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2543
telemt_desync_full_logged_total 801
telemt_desync_suppressed_total 1742
telemt_desync_frames_bucket_total{bucket="1_2"} 825
telemt_desync_frames_bucket_total{bucket="3_10"} 919
telemt_desync_frames_bucket_total{bucket="gt_10"} 799
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15503
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15291
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 557292
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 5768062230 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 157454827284 (146.64 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 76585.2 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1141929
telemt_connections_bad_total 7873
telemt_handshake_timeouts_total 107764
telemt_upstream_connect_attempt_total 20681
telemt_upstream_connect_success_total 20431
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 20681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 827
telemt_me_reconnect_attempts_total 29130
telemt_me_reconnect_success_total 15502
telemt_me_reader_eof_total 16638
telemt_me_idle_close_by_peer_total 16638
telemt_me_route_drop_no_conn_total 382551
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 982680
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2678
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 1880
telemt_desync_frames_bucket_total{bucket="1_2"} 630
telemt_desync_frames_bucket_total{bucket="3_10"} 1004
telemt_desync_frames_bucket_total{bucket="gt_10"} 1044
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 16129
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15491
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 983425
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 11423686557 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 298269460773 (277.79 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 76585.7 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824943
telemt_connections_bad_total 71919
telemt_handshake_timeouts_total 75877
telemt_upstream_connect_attempt_total 20713
telemt_upstream_connect_success_total 20713
telemt_upstream_connect_attempts_per_request{bucket="1"} 20713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 818
telemt_me_reconnect_attempts_total 17939
telemt_me_reconnect_success_total 16878
telemt_me_reader_eof_total 17917
telemt_me_idle_close_by_peer_total 17916
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 262487
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653656
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1431
telemt_desync_full_logged_total 550
telemt_desync_suppressed_total 881
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17082
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16852
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 653022
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 7494613576 (6.98 GB)
telemt_user_octets_to_client{user="hello"} 185063645772 (172.35 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76585.3 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 888166
telemt_connections_bad_total 6233
telemt_handshake_timeouts_total 8478
telemt_upstream_connect_attempt_total 21064
telemt_upstream_connect_success_total 20971
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 887
telemt_me_reconnect_attempts_total 21076
telemt_me_reconnect_success_total 17017
telemt_me_reader_eof_total 17935
telemt_me_idle_close_by_peer_total 17935
telemt_me_route_drop_no_conn_total 311572
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806132
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3319
telemt_desync_full_logged_total 1228
telemt_desync_suppressed_total 2091
telemt_desync_frames_bucket_total{bucket="1_2"} 1135
telemt_desync_frames_bucket_total{bucket="3_10"} 1303
telemt_desync_frames_bucket_total{bucket="gt_10"} 881
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17359
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17017
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 805890
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 12062725155 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 292735731082 (272.63 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 99
```