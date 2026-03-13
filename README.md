# Server Metrics 2026-03-13 17:12:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 126861.6 (35h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4039435
telemt_connections_bad_total 37515
telemt_handshake_timeouts_total 100486
telemt_upstream_connect_attempt_total 26954
telemt_upstream_connect_success_total 26777
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 26954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 5615
telemt_me_reconnect_attempts_total 28222
telemt_me_reconnect_success_total 18117
telemt_me_reader_eof_total 19459
telemt_me_idle_close_by_peer_total 19458
telemt_me_route_drop_no_conn_total 1500361
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3688240
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14445
telemt_desync_full_logged_total 3822
telemt_desync_suppressed_total 10623
telemt_desync_frames_bucket_total{bucket="1_2"} 3598
telemt_desync_frames_bucket_total{bucket="3_10"} 5478
telemt_desync_frames_bucket_total{bucket="gt_10"} 5369
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18683
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18104
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 3690410
telemt_user_connections_current{user="hello"} 1733
telemt_user_octets_from_client{user="hello"} 52046659652 (48.47 GB)
telemt_user_octets_to_client{user="hello"} 1150384802273 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 26525.7 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396823
telemt_connections_bad_total 29251
telemt_handshake_timeouts_total 10299
telemt_upstream_connect_attempt_total 7740
telemt_upstream_connect_success_total 7567
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 7740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_timeout_total 1580
telemt_me_reconnect_attempts_total 8180
telemt_me_reconnect_success_total 4786
telemt_me_reader_eof_total 5069
telemt_me_idle_close_by_peer_total 5068
telemt_me_route_drop_no_conn_total 150949
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345936
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1226
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 914
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4949
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4778
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 347274
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 3485878139 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 100889958336 (93.96 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 156482.2 (43h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2956017
telemt_connections_bad_total 28330
telemt_handshake_timeouts_total 197779
telemt_upstream_connect_attempt_total 34909
telemt_upstream_connect_success_total 34899
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3382
telemt_me_reconnect_attempts_total 29347
telemt_me_reconnect_success_total 26793
telemt_me_reader_eof_total 28411
telemt_me_idle_close_by_peer_total 28410
telemt_me_route_drop_no_conn_total 1005828
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2439109
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8488
telemt_desync_full_logged_total 2808
telemt_desync_suppressed_total 5680
telemt_desync_frames_bucket_total{bucket="1_2"} 1363
telemt_desync_frames_bucket_total{bucket="3_10"} 3109
telemt_desync_frames_bucket_total{bucket="gt_10"} 4016
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 27107
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26752
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 2438471
telemt_user_connections_current{user="hello"} 1282
telemt_user_octets_from_client{user="hello"} 40156046804 (37.40 GB)
telemt_user_octets_to_client{user="hello"} 850966732493 (792.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 156482.9 (43h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1909774
telemt_connections_bad_total 18232
telemt_handshake_timeouts_total 177863
telemt_upstream_connect_attempt_total 48822
telemt_upstream_connect_success_total 46485
telemt_upstream_connect_fail_total 2200
telemt_upstream_connect_attempts_per_request{bucket="1"} 48548
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2199
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11947
telemt_me_reconnect_attempts_total 41836
telemt_me_reconnect_success_total 32854
telemt_me_reader_eof_total 35279
telemt_me_idle_close_by_peer_total 35272
telemt_me_route_drop_no_conn_total 676602
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1571994
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3117
telemt_desync_full_logged_total 1012
telemt_desync_suppressed_total 2105
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 1283
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 33397
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32830
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 1576685
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 24342832873 (22.67 GB)
telemt_user_octets_to_client{user="hello"} 598070795862 (557.00 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 25918.8 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424237
telemt_connections_bad_total 4449
telemt_handshake_timeouts_total 4292
telemt_upstream_connect_attempt_total 5882
telemt_upstream_connect_success_total 5692
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 5882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 845
telemt_me_reconnect_attempts_total 16089
telemt_me_reconnect_success_total 4378
telemt_me_reader_eof_total 4838
telemt_me_idle_close_by_peer_total 4838
telemt_me_route_drop_no_conn_total 164147
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396428
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1257
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4778
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4374
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 396405
telemt_user_connections_current{user="hello"} 877
telemt_user_octets_from_client{user="hello"} 4532880060 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 125151975344 (116.56 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 108
```