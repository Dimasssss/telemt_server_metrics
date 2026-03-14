# Server Metrics 2026-03-14 01:07:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 155342.6 (43h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4622795
telemt_connections_bad_total 39499
telemt_handshake_timeouts_total 107996
telemt_upstream_connect_attempt_total 32832
telemt_upstream_connect_success_total 32614
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6672
telemt_me_reconnect_attempts_total 32671
telemt_me_reconnect_success_total 22537
telemt_me_reader_eof_total 24166
telemt_me_idle_close_by_peer_total 24165
telemt_me_route_drop_no_conn_total 1750879
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4237521
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16662
telemt_desync_full_logged_total 4493
telemt_desync_suppressed_total 12169
telemt_desync_frames_bucket_total{bucket="1_2"} 4152
telemt_desync_frames_bucket_total{bucket="3_10"} 6368
telemt_desync_frames_bucket_total{bucket="gt_10"} 6142
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 23177
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22524
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 640
telemt_user_connections_total{user="hello"} 4239381
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 62519931812 (58.23 GB)
telemt_user_octets_to_client{user="hello"} 1340354064357 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55006.1 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667378
telemt_connections_bad_total 49975
telemt_handshake_timeouts_total 12918
telemt_upstream_connect_attempt_total 15388
telemt_upstream_connect_success_total 15140
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 15388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 2020
telemt_me_reconnect_attempts_total 13780
telemt_me_reconnect_success_total 10338
telemt_me_reader_eof_total 10962
telemt_me_idle_close_by_peer_total 10961
telemt_me_route_drop_no_conn_total 228760
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542447
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10591
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10330
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 544398
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 5902414425 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 176638495944 (164.51 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 184962.8 (51h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3347702
telemt_connections_bad_total 34283
telemt_handshake_timeouts_total 222598
telemt_upstream_connect_attempt_total 41483
telemt_upstream_connect_success_total 41462
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10360
telemt_me_reconnect_attempts_total 36894
telemt_me_reconnect_success_total 31937
telemt_me_reader_eof_total 33907
telemt_me_idle_close_by_peer_total 33906
telemt_me_route_drop_no_conn_total 1148716
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2783151
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9167
telemt_desync_full_logged_total 3078
telemt_desync_suppressed_total 6089
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 3318
telemt_desync_frames_bucket_total{bucket="gt_10"} 4304
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 32392
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31896
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2782396
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 44947570640 (41.86 GB)
telemt_user_octets_to_client{user="hello"} 990563820909 (922.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 184965.5 (51h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2226455
telemt_connections_bad_total 22924
telemt_handshake_timeouts_total 240238
telemt_upstream_connect_attempt_total 57677
telemt_upstream_connect_success_total 55218
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 57403
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20388
telemt_me_reconnect_attempts_total 48013
telemt_me_reconnect_success_total 38985
telemt_me_reader_eof_total 41808
telemt_me_idle_close_by_peer_total 41801
telemt_me_route_drop_no_conn_total 766647
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1786486
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3801
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 39606
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38961
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 1792404
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 27410580583 (25.53 GB)
telemt_user_octets_to_client{user="hello"} 664023741150 (618.42 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54399.0 (15h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 680825
telemt_connections_bad_total 7884
telemt_handshake_timeouts_total 8615
telemt_upstream_connect_attempt_total 13439
telemt_upstream_connect_success_total 13058
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 13439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_keepalive_timeout_total 1470
telemt_me_reconnect_attempts_total 42480
telemt_me_reconnect_success_total 10323
telemt_me_reader_eof_total 11553
telemt_me_idle_close_by_peer_total 11552
telemt_me_route_drop_no_conn_total 257779
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633378
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1126
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11416
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10318
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1093
telemt_user_connections_total{user="hello"} 633277
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 10557236884 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 207496437188 (193.25 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 27
```