# Server Metrics 2026-03-11 11:37:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 76222.1 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1720455
telemt_connections_bad_total 25369
telemt_handshake_timeouts_total 44562
telemt_upstream_connect_attempt_total 15936
telemt_upstream_connect_success_total 15927
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 826
telemt_me_reconnect_attempts_total 24899
telemt_me_reconnect_success_total 12079
telemt_me_reader_eof_total 13069
telemt_me_idle_close_by_peer_total 13069
telemt_me_route_drop_no_conn_total 633055
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1565437
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8309
telemt_desync_full_logged_total 2232
telemt_desync_suppressed_total 6077
telemt_desync_frames_bucket_total{bucket="1_2"} 2091
telemt_desync_frames_bucket_total{bucket="3_10"} 3176
telemt_desync_frames_bucket_total{bucket="gt_10"} 3042
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12602
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12073
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 1564003
telemt_user_connections_current{user="hello"} 1508
telemt_user_octets_from_client{user="hello"} 20218992220 (18.83 GB)
telemt_user_octets_to_client{user="hello"} 445266871908 (414.69 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76278.9 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650915
telemt_connections_bad_total 11273
telemt_handshake_timeouts_total 40635
telemt_upstream_connect_attempt_total 24957
telemt_upstream_connect_success_total 22019
telemt_upstream_connect_fail_total 2938
telemt_upstream_connect_attempts_per_request{bucket="1"} 24957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2938
telemt_me_keepalive_timeout_total 2189
telemt_me_reconnect_attempts_total 16109
telemt_me_reconnect_success_total 15259
telemt_me_reader_eof_total 16153
telemt_me_idle_close_by_peer_total 16151
telemt_me_route_drop_no_conn_total 263764
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552050
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2533
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 1735
telemt_desync_frames_bucket_total{bucket="1_2"} 823
telemt_desync_frames_bucket_total{bucket="3_10"} 913
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15449
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15237
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 554271
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 5682880590 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 156422984916 (145.68 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 76278.9 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1134940
telemt_connections_bad_total 7841
telemt_handshake_timeouts_total 107620
telemt_upstream_connect_attempt_total 20619
telemt_upstream_connect_success_total 20369
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 20619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 826
telemt_me_reconnect_attempts_total 29098
telemt_me_reconnect_success_total 15471
telemt_me_reader_eof_total 16607
telemt_me_idle_close_by_peer_total 16607
telemt_me_route_drop_no_conn_total 380628
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976852
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2673
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1878
telemt_desync_frames_bucket_total{bucket="1_2"} 629
telemt_desync_frames_bucket_total{bucket="3_10"} 1001
telemt_desync_frames_bucket_total{bucket="gt_10"} 1043
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 16098
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15460
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 977604
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 11396608029 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 296627908729 (276.26 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 76279.3 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820622
telemt_connections_bad_total 71637
telemt_handshake_timeouts_total 75819
telemt_upstream_connect_attempt_total 20646
telemt_upstream_connect_success_total 20646
telemt_upstream_connect_attempts_per_request{bucket="1"} 20646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 816
telemt_me_reconnect_attempts_total 17906
telemt_me_reconnect_success_total 16845
telemt_me_reader_eof_total 17884
telemt_me_idle_close_by_peer_total 17883
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 260734
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 649787
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1423
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 879
telemt_desync_frames_bucket_total{bucket="1_2"} 503
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17049
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16819
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 649153
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 7457054916 (6.94 GB)
telemt_user_octets_to_client{user="hello"} 184192450216 (171.54 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76279.0 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883633
telemt_connections_bad_total 6232
telemt_handshake_timeouts_total 8458
telemt_upstream_connect_attempt_total 20929
telemt_upstream_connect_success_total 20837
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 20929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 886
telemt_me_reconnect_attempts_total 20975
telemt_me_reconnect_success_total 16916
telemt_me_reader_eof_total 17835
telemt_me_idle_close_by_peer_total 17835
telemt_me_route_drop_no_conn_total 309802
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 801732
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3310
telemt_desync_full_logged_total 1224
telemt_desync_suppressed_total 2086
telemt_desync_frames_bucket_total{bucket="1_2"} 1130
telemt_desync_frames_bucket_total{bucket="3_10"} 1302
telemt_desync_frames_bucket_total{bucket="gt_10"} 878
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17258
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 16916
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 801491
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 11971803779 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 290750767630 (270.78 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 119
```