# Server Metrics 2026-03-11 12:13:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 78365.9 (21h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1794059
telemt_connections_bad_total 25419
telemt_handshake_timeouts_total 46426
telemt_upstream_connect_attempt_total 16279
telemt_upstream_connect_success_total 16270
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 846
telemt_me_reconnect_attempts_total 25139
telemt_me_reconnect_success_total 12315
telemt_me_reader_eof_total 13320
telemt_me_idle_close_by_peer_total 13320
telemt_me_route_drop_no_conn_total 659258
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1635471
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8579
telemt_desync_full_logged_total 2310
telemt_desync_suppressed_total 6269
telemt_desync_frames_bucket_total{bucket="1_2"} 2140
telemt_desync_frames_bucket_total{bucket="3_10"} 3294
telemt_desync_frames_bucket_total{bucket="gt_10"} 3145
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12845
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12309
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 1634015
telemt_user_connections_current{user="hello"} 1323
telemt_user_octets_from_client{user="hello"} 21549423200 (20.07 GB)
telemt_user_octets_to_client{user="hello"} 463929875160 (432.07 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78422.9 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681866
telemt_connections_bad_total 12604
telemt_handshake_timeouts_total 46536
telemt_upstream_connect_attempt_total 25612
telemt_upstream_connect_success_total 22672
telemt_upstream_connect_fail_total 2940
telemt_upstream_connect_attempts_per_request{bucket="1"} 25612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2940
telemt_me_keepalive_timeout_total 2197
telemt_me_reconnect_attempts_total 16630
telemt_me_reconnect_success_total 15778
telemt_me_reader_eof_total 16698
telemt_me_idle_close_by_peer_total 16696
telemt_me_route_drop_no_conn_total 271227
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573679
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2604
telemt_desync_full_logged_total 819
telemt_desync_suppressed_total 1785
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 950
telemt_desync_frames_bucket_total{bucket="gt_10"} 823
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15975
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15756
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 575904
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 6147590382 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 163917988712 (152.66 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 78422.7 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1181501
telemt_connections_bad_total 7975
telemt_handshake_timeouts_total 111054
telemt_upstream_connect_attempt_total 21013
telemt_upstream_connect_success_total 20758
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 21013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 856
telemt_me_reconnect_attempts_total 29358
telemt_me_reconnect_success_total 15727
telemt_me_reader_eof_total 16885
telemt_me_idle_close_by_peer_total 16885
telemt_me_route_drop_no_conn_total 396424
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016459
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2707
telemt_desync_full_logged_total 806
telemt_desync_suppressed_total 1901
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 1052
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16359
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15716
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 1017201
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 11853868277 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 306618062809 (285.56 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 78423.1 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 851053
telemt_connections_bad_total 73603
telemt_handshake_timeouts_total 77458
telemt_upstream_connect_attempt_total 21232
telemt_upstream_connect_success_total 21232
telemt_upstream_connect_attempts_per_request{bucket="1"} 21232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 859
telemt_me_reconnect_attempts_total 18360
telemt_me_reconnect_success_total 17295
telemt_me_reader_eof_total 18348
telemt_me_idle_close_by_peer_total 18347
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 271754
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675977
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1450
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 889
telemt_desync_frames_bucket_total{bucket="1_2"} 515
telemt_desync_frames_bucket_total{bucket="3_10"} 525
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17505
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17268
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 675342
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 7678799812 (7.15 GB)
telemt_user_octets_to_client{user="hello"} 192613552572 (179.39 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78423.0 (21h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918183
telemt_connections_bad_total 6244
telemt_handshake_timeouts_total 8744
telemt_upstream_connect_attempt_total 21546
telemt_upstream_connect_success_total 21453
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 916
telemt_me_reconnect_attempts_total 21457
telemt_me_reconnect_success_total 17396
telemt_me_reader_eof_total 18347
telemt_me_idle_close_by_peer_total 18347
telemt_me_route_drop_no_conn_total 322611
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 834152
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3430
telemt_desync_full_logged_total 1265
telemt_desync_suppressed_total 2165
telemt_desync_frames_bucket_total{bucket="1_2"} 1162
telemt_desync_frames_bucket_total{bucket="3_10"} 1333
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17743
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17396
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 833911
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 12395634643 (11.54 GB)
telemt_user_octets_to_client{user="hello"} 302474013322 (281.70 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 108
```