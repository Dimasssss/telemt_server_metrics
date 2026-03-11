# Server Metrics 2026-03-11 12:33:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 79591.5 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1840874
telemt_connections_bad_total 27358
telemt_handshake_timeouts_total 47425
telemt_upstream_connect_attempt_total 16515
telemt_upstream_connect_success_total 16506
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 861
telemt_me_reconnect_attempts_total 25306
telemt_me_reconnect_success_total 12478
telemt_me_reader_eof_total 13502
telemt_me_idle_close_by_peer_total 13502
telemt_me_route_drop_no_conn_total 676526
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1678356
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8779
telemt_desync_full_logged_total 2370
telemt_desync_suppressed_total 6409
telemt_desync_frames_bucket_total{bucket="1_2"} 2182
telemt_desync_frames_bucket_total{bucket="3_10"} 3374
telemt_desync_frames_bucket_total{bucket="gt_10"} 3223
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13014
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12472
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 1676898
telemt_user_connections_current{user="hello"} 1600
telemt_user_octets_from_client{user="hello"} 22125091232 (20.61 GB)
telemt_user_octets_to_client{user="hello"} 475663810596 (443.00 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79648.3 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700400
telemt_connections_bad_total 13013
telemt_handshake_timeouts_total 49473
telemt_upstream_connect_attempt_total 25938
telemt_upstream_connect_success_total 22997
telemt_upstream_connect_fail_total 2941
telemt_upstream_connect_attempts_per_request{bucket="1"} 25938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2941
telemt_me_keepalive_timeout_total 2429
telemt_me_reconnect_attempts_total 16911
telemt_me_reconnect_success_total 16052
telemt_me_reader_eof_total 16987
telemt_me_idle_close_by_peer_total 16984
telemt_me_route_drop_no_conn_total 276351
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588591
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2642
telemt_desync_full_logged_total 835
telemt_desync_suppressed_total 1807
telemt_desync_frames_bucket_total{bucket="1_2"} 835
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 841
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16259
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16029
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 590804
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 6342027478 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 169333148432 (157.70 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 79648.1 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1208345
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 113998
telemt_upstream_connect_attempt_total 21361
telemt_upstream_connect_success_total 21102
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 21361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 871
telemt_me_reconnect_attempts_total 29652
telemt_me_reconnect_success_total 16017
telemt_me_reader_eof_total 17181
telemt_me_idle_close_by_peer_total 17181
telemt_me_route_drop_no_conn_total 408140
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1040014
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2822
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 1985
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 1065
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16655
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 16006
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 1040756
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 12093750209 (11.26 GB)
telemt_user_octets_to_client{user="hello"} 312762394033 (291.28 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 79648.6 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 870542
telemt_connections_bad_total 74723
telemt_handshake_timeouts_total 79824
telemt_upstream_connect_attempt_total 21706
telemt_upstream_connect_success_total 21706
telemt_upstream_connect_attempts_per_request{bucket="1"} 21706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 867
telemt_me_reconnect_attempts_total 18789
telemt_me_reconnect_success_total 17724
telemt_me_reader_eof_total 18805
telemt_me_idle_close_by_peer_total 18804
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 278899
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 691626
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1460
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 893
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17937
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17697
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 690985
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 7821089700 (7.28 GB)
telemt_user_octets_to_client{user="hello"} 197761427244 (184.18 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79648.5 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 941814
telemt_connections_bad_total 6256
telemt_handshake_timeouts_total 8860
telemt_upstream_connect_attempt_total 21806
telemt_upstream_connect_success_total 21711
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 21806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 929
telemt_me_reconnect_attempts_total 21670
telemt_me_reconnect_success_total 17606
telemt_me_reader_eof_total 18577
telemt_me_idle_close_by_peer_total 18577
telemt_me_route_drop_no_conn_total 331048
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855017
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3494
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 2203
telemt_desync_frames_bucket_total{bucket="1_2"} 1189
telemt_desync_frames_bucket_total{bucket="3_10"} 1356
telemt_desync_frames_bucket_total{bucket="gt_10"} 949
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17959
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17606
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 854773
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 12669978919 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 308368979226 (287.19 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 111
```