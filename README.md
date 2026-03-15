# Server Metrics 2026-03-15 13:13:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 53957.2 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1579589
telemt_connections_bad_total 91319
telemt_handshake_timeouts_total 14319
telemt_upstream_connect_attempt_total 10755
telemt_upstream_connect_success_total 10706
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12896
telemt_me_reconnect_success_total 8011
telemt_me_reader_eof_total 8585
telemt_me_idle_close_by_peer_total 8585
telemt_me_route_drop_no_conn_total 534215
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1331048
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4939
telemt_desync_full_logged_total 1396
telemt_desync_suppressed_total 3543
telemt_desync_frames_bucket_total{bucket="1_2"} 1256
telemt_desync_frames_bucket_total{bucket="3_10"} 1924
telemt_desync_frames_bucket_total{bucket="gt_10"} 1759
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8289
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8000
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 1330702
telemt_user_connections_current{user="hello"} 2559
telemt_user_octets_from_client{user="hello"} 18605011356 (17.33 GB)
telemt_user_octets_to_client{user="hello"} 530183023200 (493.77 GB)
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 53957.7 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 632510
telemt_connections_bad_total 32834
telemt_handshake_timeouts_total 41172
telemt_upstream_connect_attempt_total 13888
telemt_upstream_connect_success_total 13818
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10871
telemt_me_reconnect_success_total 10789
telemt_me_reader_eof_total 11400
telemt_me_idle_close_by_peer_total 11400
telemt_me_route_drop_no_conn_total 160232
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 483555
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1893
telemt_desync_full_logged_total 655
telemt_desync_suppressed_total 1238
telemt_desync_frames_bucket_total{bucket="1_2"} 712
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10912
telemt_me_writer_restored_same_endpoint_total 10777
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 483826
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 6832645575 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 181850256864 (169.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 53957.7 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1289146
telemt_connections_bad_total 41722
telemt_handshake_timeouts_total 136071
telemt_upstream_connect_attempt_total 11964
telemt_upstream_connect_success_total 11908
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10445
telemt_me_reconnect_success_total 9197
telemt_me_reader_eof_total 9739
telemt_me_idle_close_by_peer_total 9739
telemt_me_route_drop_no_conn_total 378164
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851622
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2207
telemt_desync_full_logged_total 801
telemt_desync_suppressed_total 1406
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 879
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9357
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9178
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 848116
telemt_user_connections_current{user="hello"} 1378
telemt_user_octets_from_client{user="hello"} 12435822672 (11.58 GB)
telemt_user_octets_to_client{user="hello"} 313058989016 (291.56 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 53957.6 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639037
telemt_connections_bad_total 68052
telemt_handshake_timeouts_total 35060
telemt_upstream_connect_attempt_total 55833
telemt_upstream_connect_success_total 55417
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 55831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 43968
telemt_me_reconnect_success_total 11761
telemt_me_reader_eof_total 13100
telemt_me_idle_close_by_peer_total 13100
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 166791
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435762
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 859
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12878
telemt_me_refill_failed_total 1007
telemt_me_writer_restored_same_endpoint_total 11729
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1117
telemt_user_connections_total{user="hello"} 476594
telemt_user_connections_current{user="hello"} 815
telemt_user_octets_from_client{user="hello"} 9088803871 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 165568661477 (154.20 GB)
telemt_user_msgs_from_client{user="hello"} 773857
telemt_user_msgs_to_client{user="hello"} 2693007
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 53958.6 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674917
telemt_connections_bad_total 8919
telemt_handshake_timeouts_total 13605
telemt_upstream_connect_attempt_total 11963
telemt_upstream_connect_success_total 11901
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 12877
telemt_me_reconnect_success_total 9209
telemt_me_reader_eof_total 9860
telemt_me_idle_close_by_peer_total 9860
telemt_me_route_drop_no_conn_total 167764
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547623
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2057
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1366
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9432
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9201
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 547665
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 7009851792 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 203324904452 (189.36 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 121
```