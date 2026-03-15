# Server Metrics 2026-03-15 16:58:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 67447.4 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2305744
telemt_connections_bad_total 136067
telemt_handshake_timeouts_total 28676
telemt_upstream_connect_attempt_total 13228
telemt_upstream_connect_success_total 13171
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14702
telemt_me_reconnect_success_total 9805
telemt_me_reader_eof_total 10479
telemt_me_idle_close_by_peer_total 10479
telemt_me_route_drop_no_conn_total 797371
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1938208
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7613
telemt_desync_full_logged_total 2075
telemt_desync_suppressed_total 5538
telemt_desync_frames_bucket_total{bucket="1_2"} 1845
telemt_desync_frames_bucket_total{bucket="3_10"} 2928
telemt_desync_frames_bucket_total{bucket="gt_10"} 2840
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10121
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9794
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 1937703
telemt_user_connections_current{user="hello"} 2379
telemt_user_octets_from_client{user="hello"} 28535805976 (26.58 GB)
telemt_user_octets_to_client{user="hello"} 736724818668 (686.13 GB)
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 67448.0 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 897576
telemt_connections_bad_total 47444
telemt_handshake_timeouts_total 61395
telemt_upstream_connect_attempt_total 16989
telemt_upstream_connect_success_total 16906
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 16989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14384
telemt_me_reconnect_success_total 13189
telemt_me_reader_eof_total 13956
telemt_me_idle_close_by_peer_total 13956
telemt_me_route_drop_no_conn_total 230927
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691269
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2167
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13398
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13177
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 691511
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 9952602931 (9.27 GB)
telemt_user_octets_to_client{user="hello"} 261403391284 (243.45 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 67448.1 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2021445
telemt_connections_bad_total 48568
telemt_handshake_timeouts_total 199509
telemt_upstream_connect_attempt_total 14698
telemt_upstream_connect_success_total 14629
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12500
telemt_me_reconnect_success_total 11232
telemt_me_reader_eof_total 11897
telemt_me_idle_close_by_peer_total 11897
telemt_me_route_drop_no_conn_total 523454
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1234296
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3151
telemt_desync_full_logged_total 1135
telemt_desync_suppressed_total 2016
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 1216
telemt_desync_frames_bucket_total{bucket="gt_10"} 1207
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11430
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11213
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 1230227
telemt_user_connections_current{user="hello"} 1439
telemt_user_octets_from_client{user="hello"} 18850395896 (17.56 GB)
telemt_user_octets_to_client{user="hello"} 441021096536 (410.73 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 67447.9 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 960067
telemt_connections_bad_total 80578
telemt_handshake_timeouts_total 47413
telemt_upstream_connect_attempt_total 169237
telemt_upstream_connect_success_total 168701
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 169237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 57441
telemt_me_reconnect_success_total 13267
telemt_me_reader_eof_total 15006
telemt_me_idle_close_by_peer_total 15006
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 221256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589366
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1677
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 653
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14783
telemt_me_refill_failed_total 1382
telemt_me_writer_restored_same_endpoint_total 13231
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1516
telemt_user_connections_total{user="hello"} 740990
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 13951906178 (12.99 GB)
telemt_user_octets_to_client{user="hello"} 265033835873 (246.83 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 67448.8 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 972413
telemt_connections_bad_total 12060
telemt_handshake_timeouts_total 21534
telemt_upstream_connect_attempt_total 14980
telemt_upstream_connect_success_total 14899
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 14980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 15217
telemt_me_reconnect_success_total 11526
telemt_me_reader_eof_total 12290
telemt_me_idle_close_by_peer_total 12290
telemt_me_route_drop_no_conn_total 242933
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804658
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2742
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 1821
telemt_desync_frames_bucket_total{bucket="1_2"} 847
telemt_desync_frames_bucket_total{bucket="3_10"} 1026
telemt_desync_frames_bucket_total{bucket="gt_10"} 869
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11779
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11518
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 804698
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 9929415620 (9.25 GB)
telemt_user_octets_to_client{user="hello"} 285933885396 (266.30 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 124
```