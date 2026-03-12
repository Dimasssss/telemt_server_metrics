# Server Metrics 2026-03-12 16:01:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 36178.0 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1306021
telemt_connections_bad_total 20236
telemt_handshake_timeouts_total 12714
telemt_upstream_connect_attempt_total 7219
telemt_upstream_connect_success_total 7180
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 7219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 442
telemt_me_reconnect_attempts_total 9229
telemt_me_reconnect_success_total 5320
telemt_me_reader_eof_total 5670
telemt_me_idle_close_by_peer_total 5669
telemt_me_route_drop_no_conn_total 466410
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1224128
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6361
telemt_desync_full_logged_total 1590
telemt_desync_suppressed_total 4771
telemt_desync_frames_bucket_total{bucket="1_2"} 1639
telemt_desync_frames_bucket_total{bucket="3_10"} 2287
telemt_desync_frames_bucket_total{bucket="gt_10"} 2435
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5510
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5307
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 1223811
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 19002111704 (17.70 GB)
telemt_user_octets_to_client{user="hello"} 353524310608 (329.25 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 65798.5 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 581374
telemt_connections_bad_total 7723
telemt_handshake_timeouts_total 27642
telemt_upstream_connect_attempt_total 15755
telemt_upstream_connect_success_total 15747
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 12332
telemt_me_reconnect_success_total 12262
telemt_me_reader_eof_total 13031
telemt_me_idle_close_by_peer_total 13031
telemt_me_route_drop_no_conn_total 172156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2023
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 890
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12383
telemt_me_writer_restored_same_endpoint_total 12253
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 520260
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 8029548859 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 183817042494 (171.19 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 65798.4 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1228963
telemt_connections_bad_total 6264
telemt_handshake_timeouts_total 86176
telemt_upstream_connect_attempt_total 15846
telemt_upstream_connect_success_total 15841
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1043
telemt_me_reconnect_attempts_total 13403
telemt_me_reconnect_success_total 12177
telemt_me_reader_eof_total 12832
telemt_me_idle_close_by_peer_total 12832
telemt_me_route_drop_no_conn_total 334045
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910568
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3835
telemt_desync_full_logged_total 1180
telemt_desync_suppressed_total 2655
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 1383
telemt_desync_frames_bucket_total{bucket="gt_10"} 1865
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12265
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12136
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 910745
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 12007091304 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 285227704233 (265.64 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 65799.1 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731142
telemt_connections_bad_total 7715
telemt_handshake_timeouts_total 58617
telemt_upstream_connect_attempt_total 17256
telemt_upstream_connect_success_total 17187
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 17256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1411
telemt_me_reconnect_attempts_total 19127
telemt_me_reconnect_success_total 13885
telemt_me_reader_eof_total 14806
telemt_me_idle_close_by_peer_total 14806
telemt_me_route_drop_no_conn_total 249453
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629999
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1256
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14154
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13864
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 629466
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 7920225004 (7.38 GB)
telemt_user_octets_to_client{user="hello"} 247867526488 (230.84 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65798.8 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828243
telemt_connections_bad_total 9270
telemt_handshake_timeouts_total 6748
telemt_upstream_connect_attempt_total 20702
telemt_upstream_connect_success_total 20448
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 20702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 1165
telemt_me_reconnect_attempts_total 24381
telemt_me_reconnect_success_total 17142
telemt_me_reader_eof_total 17956
telemt_me_idle_close_by_peer_total 17956
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 290283
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762522
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2967
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 1958
telemt_desync_frames_bucket_total{bucket="1_2"} 838
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 1112
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 17546
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 17104
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 762418
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 9274294680 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 214237681552 (199.52 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 132
```