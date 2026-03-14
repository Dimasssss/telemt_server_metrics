# Server Metrics 2026-03-14 06:45:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 175595.8 (48h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4944721
telemt_connections_bad_total 40205
telemt_handshake_timeouts_total 112979
telemt_upstream_connect_attempt_total 36853
telemt_upstream_connect_success_total 36612
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 36853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_timeout_total 7328
telemt_me_reconnect_attempts_total 35682
telemt_me_reconnect_success_total 25531
telemt_me_reader_eof_total 27400
telemt_me_idle_close_by_peer_total 27399
telemt_me_route_drop_no_conn_total 1872643
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4537651
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17375
telemt_desync_full_logged_total 4707
telemt_desync_suppressed_total 12668
telemt_desync_frames_bucket_total{bucket="1_2"} 4335
telemt_desync_frames_bucket_total{bucket="3_10"} 6618
telemt_desync_frames_bucket_total{bucket="gt_10"} 6422
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 26215
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25518
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 4539146
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 66411228600 (61.85 GB)
telemt_user_octets_to_client{user="hello"} 1430294417221 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75259.8 (20h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819224
telemt_connections_bad_total 53811
telemt_handshake_timeouts_total 14986
telemt_upstream_connect_attempt_total 20420
telemt_upstream_connect_success_total 20149
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2143
telemt_me_reconnect_attempts_total 17838
telemt_me_reconnect_success_total 14374
telemt_me_reader_eof_total 15277
telemt_me_idle_close_by_peer_total 15276
telemt_me_route_drop_no_conn_total 268676
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651332
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1882
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1310
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 646
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 14686
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14366
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 653248
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 6864662229 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 220764944660 (205.60 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 205216.8 (57h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3550901
telemt_connections_bad_total 41688
telemt_handshake_timeouts_total 233408
telemt_upstream_connect_attempt_total 46335
telemt_upstream_connect_success_total 46314
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10664
telemt_me_reconnect_attempts_total 40791
telemt_me_reconnect_success_total 35816
telemt_me_reader_eof_total 38044
telemt_me_idle_close_by_peer_total 38043
telemt_me_route_drop_no_conn_total 1214078
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2960124
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9772
telemt_desync_full_logged_total 3280
telemt_desync_suppressed_total 6492
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 3529
telemt_desync_frames_bucket_total{bucket="gt_10"} 4541
telemt_pool_swap_total 194
telemt_me_writer_removed_unexpected_total 36314
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35775
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 2959275
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 49279743028 (45.90 GB)
telemt_user_octets_to_client{user="hello"} 1057456964865 (984.83 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 205219.2 (57h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2369029
telemt_connections_bad_total 23300
telemt_handshake_timeouts_total 280152
telemt_upstream_connect_attempt_total 63902
telemt_upstream_connect_success_total 61413
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 63628
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20513
telemt_me_reconnect_attempts_total 53251
telemt_me_reconnect_success_total 44205
telemt_me_reader_eof_total 47390
telemt_me_idle_close_by_peer_total 47383
telemt_me_route_drop_no_conn_total 798401
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1868850
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3906
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 2640
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 182
telemt_me_writer_removed_unexpected_total 44871
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44181
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 1874902
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 28275971099 (26.33 GB)
telemt_user_octets_to_client{user="hello"} 689797008746 (642.42 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74652.6 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792436
telemt_connections_bad_total 8105
telemt_handshake_timeouts_total 9357
telemt_upstream_connect_attempt_total 18954
telemt_upstream_connect_success_total 18446
telemt_upstream_connect_fail_total 508
telemt_upstream_connect_attempts_per_request{bucket="1"} 18954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 508
telemt_me_keepalive_timeout_total 1572
telemt_me_reconnect_attempts_total 60046
telemt_me_reconnect_success_total 14740
telemt_me_reader_eof_total 16521
telemt_me_idle_close_by_peer_total 16520
telemt_me_route_drop_no_conn_total 305115
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 740239
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1791
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 1218
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 562
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16283
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14735
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1543
telemt_user_connections_total{user="hello"} 740102
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 13125694000 (12.22 GB)
telemt_user_octets_to_client{user="hello"} 248576191124 (231.50 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 70
```