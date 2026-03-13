# Server Metrics 2026-03-13 22:24:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 145527.8 (40h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4526405
telemt_connections_bad_total 38368
telemt_handshake_timeouts_total 107038
telemt_upstream_connect_attempt_total 30377
telemt_upstream_connect_success_total 30169
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6640
telemt_me_reconnect_attempts_total 30708
telemt_me_reconnect_success_total 20587
telemt_me_reader_eof_total 22092
telemt_me_idle_close_by_peer_total 22091
telemt_me_route_drop_no_conn_total 1709067
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4147067
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16518
telemt_desync_full_logged_total 4438
telemt_desync_suppressed_total 12080
telemt_desync_frames_bucket_total{bucket="1_2"} 4112
telemt_desync_frames_bucket_total{bucket="3_10"} 6313
telemt_desync_frames_bucket_total{bucket="gt_10"} 6093
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 21202
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20574
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 4149198
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 60985059740 (56.80 GB)
telemt_user_octets_to_client{user="hello"} 1311077353973 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45191.5 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 591418
telemt_connections_bad_total 42931
telemt_handshake_timeouts_total 12433
telemt_upstream_connect_attempt_total 12748
telemt_upstream_connect_success_total 12521
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 12748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1909
telemt_me_reconnect_attempts_total 11634
telemt_me_reconnect_success_total 8204
telemt_me_reader_eof_total 8696
telemt_me_idle_close_by_peer_total 8695
telemt_me_route_drop_no_conn_total 215884
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511762
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8429
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8196
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 513691
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 5572980737 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 167359338172 (155.87 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 175148.3 (48h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3289928
telemt_connections_bad_total 31802
telemt_handshake_timeouts_total 219912
telemt_upstream_connect_attempt_total 38828
telemt_upstream_connect_success_total 38807
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10290
telemt_me_reconnect_attempts_total 34718
telemt_me_reconnect_success_total 29766
telemt_me_reader_eof_total 31591
telemt_me_idle_close_by_peer_total 31590
telemt_me_route_drop_no_conn_total 1127411
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2731681
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8984
telemt_desync_full_logged_total 3022
telemt_desync_suppressed_total 5962
telemt_desync_frames_bucket_total{bucket="1_2"} 1507
telemt_desync_frames_bucket_total{bucket="3_10"} 3256
telemt_desync_frames_bucket_total{bucket="gt_10"} 4221
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 30205
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29725
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 2730940
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 44599069988 (41.54 GB)
telemt_user_octets_to_client{user="hello"} 966609252301 (900.23 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 175150.9 (48h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2150215
telemt_connections_bad_total 22833
telemt_handshake_timeouts_total 218663
telemt_upstream_connect_attempt_total 54489
telemt_upstream_connect_success_total 52040
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54215
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20323
telemt_me_reconnect_attempts_total 45311
telemt_me_reconnect_success_total 36294
telemt_me_reader_eof_total 38941
telemt_me_idle_close_by_peer_total 38934
telemt_me_route_drop_no_conn_total 754189
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1755127
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3794
telemt_desync_full_logged_total 1215
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 36890
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36270
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 1761009
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 27284737567 (25.41 GB)
telemt_user_octets_to_client{user="hello"} 657948144506 (612.76 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44584.5 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633662
telemt_connections_bad_total 6740
telemt_handshake_timeouts_total 5976
telemt_upstream_connect_attempt_total 10129
telemt_upstream_connect_success_total 9803
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 10129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_keepalive_timeout_total 1428
telemt_me_reconnect_attempts_total 35928
telemt_me_reconnect_success_total 7557
telemt_me_reader_eof_total 8576
telemt_me_idle_close_by_peer_total 8575
telemt_me_route_drop_no_conn_total 241119
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592606
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8514
telemt_me_refill_failed_total 883
telemt_me_writer_restored_same_endpoint_total 7552
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 957
telemt_user_connections_total{user="hello"} 592517
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 8945962496 (8.33 GB)
telemt_user_octets_to_client{user="hello"} 191664297844 (178.50 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 39
```