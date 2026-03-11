# Server Metrics 2026-03-11 21:14:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 110835.1 (30h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2803302
telemt_connections_bad_total 64745
telemt_handshake_timeouts_total 62585
telemt_upstream_connect_attempt_total 23662
telemt_upstream_connect_success_total 23650
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5440
telemt_me_reconnect_attempts_total 35914
telemt_me_reconnect_success_total 18017
telemt_me_reader_eof_total 19437
telemt_me_idle_close_by_peer_total 19437
telemt_me_route_drop_no_conn_total 1051289
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2541959
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12722
telemt_desync_full_logged_total 3534
telemt_desync_suppressed_total 9188
telemt_desync_frames_bucket_total{bucket="1_2"} 3143
telemt_desync_frames_bucket_total{bucket="3_10"} 4884
telemt_desync_frames_bucket_total{bucket="gt_10"} 4695
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 18784
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 18011
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 767
telemt_user_connections_total{user="hello"} 2540292
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 38647060152 (35.99 GB)
telemt_user_octets_to_client{user="hello"} 733188627876 (682.84 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 110891.5 (30h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1022067
telemt_connections_bad_total 17056
telemt_handshake_timeouts_total 90470
telemt_upstream_connect_attempt_total 33765
telemt_upstream_connect_success_total 30786
telemt_upstream_connect_fail_total 2979
telemt_upstream_connect_attempts_per_request{bucket="1"} 33765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2979
telemt_me_keepalive_timeout_total 2913
telemt_me_reconnect_attempts_total 24372
telemt_me_reconnect_success_total 22242
telemt_me_reader_eof_total 23575
telemt_me_idle_close_by_peer_total 23572
telemt_me_route_drop_no_conn_total 386712
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854815
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3378
telemt_desync_full_logged_total 1101
telemt_desync_suppressed_total 2277
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 22570
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22219
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 857251
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 10338603242 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 257588281892 (239.90 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 110891.5 (30h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1784856
telemt_connections_bad_total 11366
telemt_handshake_timeouts_total 136841
telemt_upstream_connect_attempt_total 37305
telemt_upstream_connect_success_total 36946
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 37305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 2058
telemt_me_reconnect_attempts_total 62359
telemt_me_reconnect_success_total 20668
telemt_me_reader_eof_total 22830
telemt_me_idle_close_by_peer_total 22830
telemt_me_route_drop_no_conn_total 645711
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1560723
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4213
telemt_desync_full_logged_total 1243
telemt_desync_suppressed_total 2970
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22253
telemt_me_refill_failed_total 1297
telemt_me_writer_restored_same_endpoint_total 20656
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1585
telemt_user_connections_total{user="hello"} 1569918
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 19999013712 (18.63 GB)
telemt_user_octets_to_client{user="hello"} 479902844466 (446.94 GB)
telemt_user_msgs_from_client{user="hello"} 130604
telemt_user_msgs_to_client{user="hello"} 683584
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 110891.8 (30h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1277162
telemt_connections_bad_total 78279
telemt_handshake_timeouts_total 111768
telemt_upstream_connect_attempt_total 29768
telemt_upstream_connect_success_total 29768
telemt_upstream_connect_attempts_per_request{bucket="1"} 29768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1554
telemt_me_reconnect_attempts_total 28823
telemt_me_reconnect_success_total 24203
telemt_me_reader_eof_total 25711
telemt_me_idle_close_by_peer_total 25710
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 428774
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051160
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24607
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24170
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 1050281
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 12323345040 (11.48 GB)
telemt_user_octets_to_client{user="hello"} 317822752348 (296.00 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15567.8 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214103
telemt_connections_bad_total 5176
telemt_handshake_timeouts_total 2420
telemt_upstream_connect_attempt_total 4509
telemt_upstream_connect_success_total 4508
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 3687
telemt_me_reconnect_success_total 3653
telemt_me_reader_eof_total 3793
telemt_me_idle_close_by_peer_total 3793
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 72627
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189466
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 475
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 169
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3696
telemt_me_writer_restored_same_endpoint_total 3627
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 189428
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 9675485312 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 65715332496 (61.20 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 45
```